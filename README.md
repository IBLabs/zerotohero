![Niran Dishi](https://i.ibb.co/ZhSjWkk/niran-header.png)

# Niran: Zero to Hero

Welcome to Niran's "Zero to Hero" exercise! We're going to get you from a simple Python student to an awesome developer in no-time! Provided you follow the instructions and stay motivated!

## Assignment 1: Capital Cities

In this 1st assignment we are going to familiar with some basic real-world python programming! We are going to create a script that fetches the list of the world's capital cities, does some manipulations and creates a new JSON file that contains the new modified values.

### Prerequisites

These are the things you need to know before starting this assignment -

* **HTTP Requests**
* What is an HTTP request?
* What are the different types of HTTP requests? (GET, POST etc.)
* Specifically, what is a **POST** request?
* Specifically, what is a **GET** request?
* What is the difference between GET and POST requests? [Read More](https://www.w3schools.com/tags/ref_httpmethods.asp)
* **JSON**
* What is JSON? [Read More](https://www.w3schools.com/js/js_json_intro.asp)
* What is the structure of a JSON object?
* **Python File Manipulation**
* How do you **create** a text file in python? [Read More](https://stackoverflow.com/questions/48959098/how-to-create-a-new-text-file-using-python)
* How do you **delete** a file in python? [Read More](https://stackoverflow.com/questions/6996603/delete-a-file-or-folder)
* How do you **rename** a file in python [Read More](https://stackoverflow.com/questions/2491222/how-to-rename-a-file-using-python)
* **Python Packages**
* What is PIP? [Read More](https://www.w3schools.com/python/python_pip.asp)
* **Python HTTP Requests**
* Get to know the **Requests** python library [Read More](http://docs.python-requests.org/en/master/)
* How do you install the Requests library? (*hint: use* `pip`)
* How do you perform a simple GET request?
* How do you perform a simple POST request?

### Objective

Create a script that connects to the [REST Countries API](https://restcountries.eu/) and requests the list of the world's countries. After receiving the list, the script will **add 1 key-value pair** to each one of the returned countries' JSON dictionaries in the following format:

"flag_url": "[THE_FLAG_URL]"

Where `[THE_FLAG_URL]` is an actual URL address of a PNG file of the country's flag - you can use [Country Flags API](https://countryflags.io/) to get the images of the countries' flags.

#### What Should I Do?

Now we will list the steps you should perform to create the following script, make sure to follow the instructions slowly, and if you get stuck, just give me a call!

* **Completed!** ✅ ~~**Step 1:** Create a python script that requests the list of countries from the [REST Countries API](https://restcountries.eu/) and prints it to the console~~
* **Completed!** ✅ ~~**Step 2:** Each country inside the received JSON dictionary has an Alpha 2 code, parse the response into a python dictionary and print *only* the Alpha 2 codes of the countries from the received JSON~~
* **Conmpleted!** ✅~~St**ep 2.1:** *Instead* of printing the Alpha 2 codes, save them to a text file named `alpha2codes.txt`~~
* **Step 3:** Alright, we are steppin' it up a bit, this time we're going to get some information from all kinds of sources. Now, you're going to get the array of countries, look up the country's capital using Google Map's geocoding API, get the country's capital coordinates and it's flag using the flag API, and print them in a JSON dictionary!
* **Step 3.1:** Signup to Google Map's geocoding API and get youer own API key
* **Step 3.2:** Get the list of countries using the REST Countries API and construct a list of capital cities addresses in the form of "[CITY NAME], [COUNTRY NAME]" (e.g. Jerusalem, Israel)
* **Step 3.3:** Send the constructed strings to Google's geocoding API to get geographical information on the destination, including it's coordinates.
* **Step 3.4:** Create an array of JSON dictionaries that contain the following information about each city:
1. The city's name under the `name` key
2. The country's name under the `country` key
3. The latitude coordinate under the `lat` key
4. The longitude coordinate unre the `lon` key
5. A URL address to the country's flag undek the `flag_url` key
* **Step 3.5:** Save the array of JSON dictionaries to a file named `niran_rocks.txt`

здоровье! (which is 'Cheers' in Russian 😂)
