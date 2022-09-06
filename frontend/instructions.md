# RepReach Frontend Product Exercise

```
TIMEBOX:    3-6 hours max. 
LANGUAGES:  Typescript
FRAMEWORKS: React or React-Native and any libraries you want
TESTS:	    nice to have, but not mandatory
DOCS:       nice to have, but not mandatory
```

# Overview
This exercise is to implement the best possible solution to the below exercise. We’re evaluating your ability to take a set of requirements and build a holistic solution that demonstrates craftsmanship, thoughtfulness, and attention to user experience. We’re looking for something that is beautiful, intuitive, and easy to debug/test/extend.

# Exercise A

### I am a sales rep using an app (web or mobile) to view and analyze doctors  
1. View a list of doctors in my area
2. Filter the list of doctors by free text search
3. Filter the list of doctors by different properties
	1. See only doctors that have scheduling enabled
	2. **Stretch Goal** Filter a list of doctors by specific procedures (i.e. only doctors that do Botox) 

## API Spec
The doctor data will come from the following api:
#### NOTE: 
You do not need to create an api or database layer. You can just mock results. The example data is found in [doctor_data.json](frontend/doctor_data.json)
```
GET /api/v1/doctors

RESPONSE
[
  {
    "npi": "abc1234",
    "first_name": "John",
    "last_name": "Smith",
    "title": "MD",
    "scheduling_enabled": true,
    "image_url": "https://demo-image-200x200.jpg",
    "primary_specialty": {
   	"specialty": "Dermatology",
  	"id": 1
    },
    "procedures": [
       {
         "procedure_id": 1,
         "name": "Botox"
       },
       ...
    ],
  },
  ...
]
```


### Bonus points for using the following: 
* create-react-app (with typescript)
* ReactJs or React Native
* Tailwindcss
* Next.js
