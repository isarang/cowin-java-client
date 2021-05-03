# cowin-java-client
Java SDK for COWIN Service


#Usage
```
    ApiClient client = new ApiClient();
    client.setBasePath("https://cdn-api.co-vin.in/api");

    InlineResponse2005 response2 =
        new AppointmentAvailabilityApIsApi(client).calendarByPin("441904", "04-05-2021", "en_IN");
    System.out.println(response2);
```