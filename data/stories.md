## simple1
* greet
 - utter_ask_howcanhelp
* inform{"category": "pants"}
 - utter_on_it
 - utter_ask_morecategory
* inform{"detailcategory": "short"}
 - utter_ask_gender
* inform{"gender": "male"}
 - utter_ask_size
* inform{"size":"M"}
 - utter_ask_color
* inform{"color":"black"} 
 - utter_ask_price_range
* inform{"price_range": "under $100"}
 - utter_ask_type
* inform{"type": "authentic brand"}
 - utter_ask_moreupdates
* inform{"age":"18"}
 - utter_ask_moreupdates
* deny
 - utter_ack_dosearch
 - action_search_item
 - action_suggest
* deny
 - utter_ack_findalternatives
 - action_suggest
* deny
 - utter_ack_findalternatives
 - action_suggest
* affirm
 - utter_ack_makeorder
* thankyou
 - utter_goodbye

## simple2:stringinput1
* greet
 - utter_ask_howcanhelp
* inform{"category": "pants", "detailcategory": "short", "color": "black"}
 - utter_on_it
 - utter_ask_gender
* inform{"gender": "male"}
 - utter_ask_size
* inform{"size": "M"}
 - utter_ask_type
* inform{"type": "authentic brand"}
 - utter_ask_price_range
* inform{"price": "under $100"}
 - utter_ask_moreupdates
* deny
 - utter_ack_dosearch
 - action_search_restaurants
 - action_suggest
* deny
 - utter_ack_findalternatives
 - action_suggest
* deny
 - utter_ack_findalternatives
 - action_suggest
* affirm
 - utter_ack_makeorder
* thankyou
 - utter_goodbye

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye
