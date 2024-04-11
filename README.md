# linkLocator
Generate a unique tracking HTML link

This code creates a form where users can input a URL, and when submitted, it generates a tracking link with a unique ID appended to it. The generated link is displayed in a Google Maps InfoWindow, and it can be clicked to open in a new tab. When someone clicks on the link, the location of the device will be attempted to be retrieved using Google location services. If that fails, it will resort to deriving the location using the IP address. 
