
# Phone Book

## Objective - To implement a PhoneBook class which maps a name to many phoneNumber

### Purpose - To establish familiarity with List and Maps in a project

***You can use an associative data type (one which stores items as keys paired with values)***

### Your PhoneBook class should have the following methods:

- void add(String name, String phoneNumber)
  - adds an entry to the composite associate data type

- void addAll(String name, String... phoneNumbers)
  - adds many phone numbers to a single name entry

- void remove(String name)
  - removes an entry to the composite associate data type

- Boolean hasEntry(String name)
  - returns true if name exits in phone book else false

- List<String> lookup(String name)
  - returns a phone number(s) for the respective input name

- String reverseLookup(String phoneNumber)
  - returns a name for the respective input phoneNumber

- String getAllContactNames()
  - returns a list of all names in this PhoneBook


### Write test cases for the following:
- AddALL()
- Remove()
- ReverseLookUp()
