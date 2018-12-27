# ohs
Added 2 APIs  Jobs/Job API need to be changed as per the requested Key Value pair from App Team - 

1. Login API

URL - https://safety.pyrogroup.com

Path - /OHS/login

Request Type - application/json

Request - {"username":"7904","password":"7904"}

Response - {"catogery":"COORDINATOR","empid":"7904","password":"7904","loginid":"ATMURI SAI","cricle":"Telangana","id":197,"username":"ATMURI SAI BABU","token":"25BRGYPMFU5F","status":"Active"}
==============================================================================================================================================

2.1 Job API

URL - https://safety.pyrogroup.com

Path - /OHS/Jobs

Request Type - application/json

Authorization : Bearer Token : 25BRGYPMFU5F(Login User token)

Request - 
{
	"id":"1"
}

Response - 

{
    "notes": "123",
    "endDate": "2018-12-29",
    "addedBy": "7904",
    "activityName": "Installation",
    "siteName": "123",
    "doneBy": "pyro",
    "customerPrice": "21312",
    "operator": "Airtel",
    "jobId": 1,
    "cdt": "2018-12-26",
    "paymode": "cashandcarry",
    "siteID": "12345",
    "vendorPrice": "2132",
    "resourcename": "Pyro1",
    "siteidwrtpo": "1232",
    "activitydesc": "12312",
    "pyroname": "Pyro1",
    "tada": "123",
    "vendorname": "Vendor1",
    "PM": "213",
    "PN": "SAMSUNG",
    "startDate": "2018-12-13"
}
==============================================================================================================================================
2.2Jobs API

URL - https://safety.pyrogroup.com

Path - /OHS/Jobs

Request Type - application/json

Authorization : Bearer Token : 25BRGYPMFU5F(Login User token)

Request - 

Response - 
{
    "circleResponses": {
        "modifiedTime": "2018-06-12 15:54:00.0",
        "deleted": false,
        "name": "ANDHRA PRADESH and TELANGANA",
        "customerId": 92,
        "createdTime": "2018-06-12 15:54:00.0",
        "circleId": 16
    },
    "totalJobStatusCounts": [
        {
            "notes": "123",
            "endDate": "2018-12-29",
            "addedBy": "7904",
            "activityName": "Installation",
            "siteName": "123",
            "doneBy": "pyro",
            "customerPrice": "21312",
            "operator": "Airtel",
            "jobId": 1,
            "cdt": "2018-12-24",
            "paymode": "cashandcarry",
            "siteID": "12345",
            "vendorPrice": "2132",
            "resourcename": "Pyro1",
            "siteidwrtpo": "1232",
            "activitydesc": "12312",
            "pyroname": "Pyro1",
            "tada": "123",
            "vendorname": "Vendor1",
            "PM": "213",
            "PN": "SAMSUNG",
            "startDate": "2018-12-13"
        },
        {
            "notes": "la la la lal laaaaa",
            "endDate": "2018-12-30",
            "addedBy": "7904",
            "activityName": "2G",
            "siteName": "Ameerpeth Site",
            "doneBy": "pyro",
            "customerPrice": "123",
            "operator": "Airtel",
            "jobId": 2,
            "cdt": "2018-12-24",
            "paymode": "cashandcarry",
            "siteID": "101Ameer",
            "vendorPrice": "1096",
            "resourcename": "test123",
            "siteidwrtpo": "Site101",
            "activitydesc": "2g installation",
            "pyroname": "12312",
            "tada": "121",
            "vendorname": "pyro",
            "PM": "Avanish",
            "PN": "SAMSUNG",
            "startDate": "2018-12-08"
        }
    ]
}