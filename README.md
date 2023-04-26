# NammaYatriNoMap

Video demo: https://youtu.be/PXkv3mYnMbs

Website demo: https://sarthaks97.github.io/NammaYatriNoMap/

# Instructions
1. Fill in your name and number
2. To find your location co-ordinates, go to Google Maps and find a road nearest to you. Long press on it to drop a pin
3. Swipe up to find the co-ordinates. Long press on it to copy to clipboard. Paste it in the "Your Location" field
4. Do the same for the destination co-ordinates
5. Now click Estimate Price to find the distance and estimated price for the ride
6. If you want to proceed, click Book Now

# Disclaimer
This project is only a demo. It is to showcase how to use navigation in a mobility app without the use of Google Maps API. Infact the website doesn't even have a backend. The variables are stored in localStorage and displayed on a different page.

## Some notes for production
When it is to be deployed, the location data filled by the user can be stored in a database. The driver will see a list of bookings (queried from the database) nearby. To connect the users with the nearby driver, navigator.geolocation.getcurrentposition() on the driver's phone can be used. 

