<!---
uzaijam/uzaijam is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
---> $hotel = new \uzaijam\BookingComClient\Hotel();
$data = $hotel->getHotelByDestinationId('20088325', 1)
getHotelByDestinationId accepts destination ID and number of hotels to return.

output from $data in json format

[
    {
        "hotel_id": 21985,
        "hotel_data": {
            "district_id": 929,
            "number_of_reviews": 870,
            "class_is_estimated": false,
            "creditcard_required": true,
            "book_domestic_without_cc_details": false,
            "hotel_important_information": "Please note that as of April 2021, the hotel no longer has an indoor pool. Please note that as of May, 2021, the hotel provides transportation\/taxi assistance and luggage storage\/carry service. Self-service lockers are available upon request.\nGuests are required to show a photo identification and credit card upon check-in. Please note that all Special Requests are subject to availability and additional charges may apply. Due to COVID19 we need to be extra careful and do the needy to prevent",
            "review_score": 8.1,
            "hotel_type_id": 204,
            "deep_link_url": "booking:\/\/hotel\/21985?affiliate_id=964078",
            "city_id": 20088325,
            "name": "Courtyard New York Manhattan\/Upper East Side",
            "city": "New York",
            "max_rooms_in_reservation": 9,
            "number_of_rooms": 226,
            "checkin_checkout_times": {
                "checkin_to": "00:00",
                "checkin_from": "15:00",
                "checkout_to": "12:00",
                "checkout_from": ""
            },
            "zip": "NY 10128",
            "location": {
                "longitude": -73.94608,
                "latitude": 40.78029
            },
            "exact_class": 3,
            "spoken_languages": [
                "ru",
                "pt",
                "ko",
                "hi",
                "es",
                "en"
            ],
            "max_persons_in_reservation": 0,
            "address": "410 East 92nd Street",
            "chain_id": [
                1093
            ],
            "country": "us",
            "ranking": 2345121,
            "hotel_description": "Located in Manhattan\u2019s Upper East Side, this hotel is within 15 minutes\u2019 walk from Guggenheim Museum and Central Park. A fitness centre is available. All rooms include free Wi-Fi.",
            "preferred": false,
            "url": "https:\/\/www.booking.com\/hotel\/us\/manhattan-upper-east-side-courtyard-by-marriott.html",
            "default_language": "en",
            "class": 3,
            "currency": "USD"
