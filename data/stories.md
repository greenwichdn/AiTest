## story1_positive1
* greet
 - utter_greet
 - utter_ask_inquire
* inform
 - utter_ask_category
* give_category{"category": "pants"}
 - utter_ask_gender
* inform{"gender": "male"}
 - utter_ask_size
* inform{"size":"M"}
 - utter_ask_color
* inform{"color":"black"} 
 - utter_ask_brand
* inform{"brand": "authentic brand"}
 - utter_ask_age
* inform{"age":"18"}
 - utter_ask_more
* deny
 - utter_acknowledge
 - utter_ack_order
* affirm
* thanks
* goodbye
 - utter_goodbye
 
## story1_positive2
* greet
 - utter_ask_inquire
* inform{"category": "pants"}
 - utter_on_it
 - utter_ask_more
* inform{"category": "short"}
 - utter_ask_gender
* inform{"gender": "male"}
 - utter_ask_size
* inform{"size":"M"}
 - utter_ask_color
* inform{"color":"black"} 
 - utter_ask_more
* deny
 - utter_acknowledge
 - action_search_item
 - action_suggest
* deny
 - action_suggest
* deny
 - utter_ask_more
* inform{"type": "authentic brand"}
 - utter_ask_ore
* inform{"age":"18"}
 - utter_ask_more
* deny
 - action_suggest
* affirm
 - utter_ack_order
* goodbye


## story1_positive3
* greet
 - utter_ask_inquire
* inform{"category": "pants"}
 - utter_on_it
 - utter_ask_gender
* inform{"gender": "male"}
 - utter_ask_size
* inform{"size":"M"}
 - utter_ask_color
* inform{"color":"black"} 
 - utter_ask_more
* deny
 - utter_acknowledge
 - action_search_item
 - action_suggest
* deny
 - utter_ack_find_alternatives
 - action_suggest
* affirm
 - utter_ask_more
* deny
  - utter_ack_order
  - utter_goodbye
* goodbye


## sad path 2
* greet
  - utter_greet
* mood_sadness
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_goodbye

