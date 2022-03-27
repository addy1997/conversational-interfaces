## Generated Story 3320800183399695936
* greet
    - utter_greet
* inform
    - utter_ask_location
* inform{"location": "italy"}
    - slot{"location": "italy"}
    - action_weather
    - slot{"location": "italy"}
* goodbye
    - utter_goodbye
    - export

## story_1
* greet
    - utter_greet
* GetWeather{"date": "March 7th"}
    - utter_working_on_it
    - action_weather
* GetWeather{"location": "Dixon", "date": "March 7th"}
    - action_weather
* goodbye
   - utter_goodbye

## story_2
* greet
    - utter_greet
* GetWeather{"location": "sonoma", "date": "9th of this month"}
    - action_weather
* GetDetails{"request": "humidity"}
    - action_weather
* goodbye
   - utter_goodbye

## story_3
* greet
    - utter_greet
* GetWeather{"date": "March 14th"}
    - utter_working_on_it
    - action_weather
* GetWeather{"location": "Mill Valley", "date": "March 14th"}
    - action_weather
* GetDetails{"request": ["humidity", "wind"]}
    - action_weather
* GetWeather{"location": "Palo Alto", "date": "next Tuesday"}
    - action_weather
* goodbye
   - utter_goodbye

## story_4
* greet
    - utter_greet
* GetWeather{"location": "Mountain View"}
    - action_weather
* goodbye
    - utter_goodbye

## story_5
* greet
    - utter_greet
* GetWeather{"date": "March 9th"}
    - action_weather
* GetWeather{"location": "Yountville", "date": "March 9th"}
    - action_weather
* goodbye
    - utter_goodbye

## story_6
* greet
    - utter_greet
* GetWeather{"date": "March 8th"}
    - utter_working_on_it
    - action_weather
* GetWeather{"location": "Menlo Park", "date": "March 8th"}
    - action_weather
* goodbye
    - utter_goodbye

## story_7
* greet
    - utter_greet
* GetWeather{date": "Thursday next week"}
    - action_weather
* GetWeather{"location": "Sebastopol", "date": "Thursday next week"}
    - action_weather
* GetDetails{"request": ["humidity", "wind"]}
    - action_weather
* GetWeather{"location": "Mill Valley", "date": "Thursday next week"}
    - action_weather
* goodbye
    - utter_goodbye

## story_8
* greet
    - utter_greet
* GetWeather{"date": "March 9th"}
    - action_weather
* GetWeather{"location": "Fairfax", "date": "March 9th"}
    - action_weather

* goodbye
    - utter_goodbye

## story_9
* greet
    - utter_greet
* GetWeather{"location": "San Fran", "date": "4th of this month"}
    - action_weather
* goodbye
    - utter_goodbye

## story_10
* greet
    - utter_greet
* GetWeather{"location": "Novato", "date": "March 13th"}
    - action_weather
* goodbye
    - utter_goodbye

## story_11
* greet
    - utter_greet
* GetWeather{"location": "Campbell", "date": "March 1st"}
    - action_weather
* goodbye
    - utter_goodbye

## story_12
* greet
    - utter_greet
* GetWeather{"date": "March 7th"}
    - utter_working_on_it
    - action_weather
* GetWeather{"location": "San Jose", "date": "March 7th"}
    - action_weather
* goodbye
    - utter_goodbye

## story_13
* greet
    - utter_greet
* GetWeather{"date": "the 7th"}
    - utter_working_on_it
    - action_weather
* GetWeather{"location": "Ciudad de Mexico", "date": "the 7th"}
    - action_weather
* GetDetails{"request": ["humidity", "wind"]}
    - action_weather
* goodbye
    - utter_goodbye

## story_14
* greet
    - utter_greet
* GetWeather{"location": "Hercules"}
   - action_weather
* goodbye
    - utter_goodbye

## story_15
* greet
    - utter_greet
* GetWeather{"location": "Millbrae", "date": "March 6th"}
    - action_weather
* goodbye
    - utter_goodbye

## story_16
* greet
    - utter_greet
* GetWeather
    - action_weather
* GetWeather{"location":"Berkeley"}
    - action_weather
* GetWeather{"location": "Berkeley", "date": "March 6th"}
    - action_weather
* GetWeather{"location": "Long Beach", "date": "13th of March}
    - action_weather
* goodbye
    - utter_goodbye

## story_17
* greet
    - utter_greet
* GetWeather{"location": "calistoga", "date": "3rd of this month"}
    - action_weather
* GetDetails{"request": "humidity"}
    - action_weather
* goodbye
    - utter_goodbye

## story_18
* greet
    - utter_greet
* GetWeather{"location": "Pleasant Hill", "date": "9th of March}
    - action_weather
* goodbye
    - utter_goodbye

## story_19
* greet
    - utter_greet
GetWeather{"location": "Hercules"}
   - action_weather
* goodbye
    - utter_goodbye

## story_20
* greet
    - utter_greet
* GetWeather{"location": "Hercules", "date": "Wednesday next week"}
    - action_weather
* GetDetails{"request": "wind"}
    - action_weather
* goodbye
    - utter_goodbye
