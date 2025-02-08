import phonenumbers
from phonenumbers import geocoder

number = "+918610634215"
parsed_number = phonenumbers.parse(number)
location = geocoder.description_for_number(parsed_number, "en")
print(location)

