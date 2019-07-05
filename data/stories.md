## story1_positive1
* greet
 - utter_greet
 - utter_ask_howcanhelp
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
<<<<<<< HEAD
* thankyou
=======
* goodbye

## story1_positive2
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
 - utter_ask_moreupdates
* deny
 - utter_ack_dosearch
 - action_search_item
 - action_suggest
* deny
 - utter_ack_findalternatives
 - action_suggest
* deny
 - utter_ask_moreupdates
* inform{"type": "authentic brand"}
 - utter_ask_moreupdates
* inform{"age":"18"}
 - utter_ask_moreupdates
* deny
 - utter_ack_findalternatives
 - action_suggest
* deny
 - utter_ack_findalternatives
 - action_suggest 
* affirm
 - utter_ack_makeorder
* goodbye

## story1_positive3
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
 - utter_ask_moreupdates
* deny
 - utter_ack_dosearch
 - action_search_item
 - action_suggest
* deny
 - utter_ack_findalternatives
 - action_suggest
* deny
 - utter_ask_moreupdates
* inform{"type": "authentic brand"}
 - utter_ask_moreupdates
* deny
 - utter_ack_findalternatives
 - action_suggest
* deny
 - utter_ack_findalternatives
 - action_suggest
 - utter_ask_moreupdates
* inform{"age":"18"}
 - utter_ack_findalternatives
 - action_suggest
*deny
 - utter_ack_findalternatives
 - action_suggest 
* affirm
 - utter_ack_makeorder
>>>>>>> 8d1750abd62e5329f2bafa6e3bedab4e19c5ee0b
* goodbye

## story2_negative1
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
* deny
 - utter_ack_findalternatives
 - action_suggest
* deny
 - utter_ack_findalternatives
 - action_suggest 
* deny
 - utter_ask_moreupdates
* deny
 - utter_ask_anythingelse
* deny
* goodbye

## story2_negative2
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
 - utter_ask_moreupdates
* deny
 - utter_ack_dosearch
 - action_search_item
 - action_suggest
* deny
 - utter_ack_findalternatives
 - action_suggest
* deny
 - utter_ask_moreupdates
* inform{"type": "authentic brand"}
 - utter_ask_moreupdates
* inform{"age":"18"}
 - utter_ask_moreupdates
* deny
 - utter_ack_findalternatives
 - action_suggest
* deny
 - utter_ack_findalternatives
 - action_suggest 
* deny
 - utter_ask_moreupdates
* deny
 - utter_ask_anythingelse
* deny
* goodbye

## story3:stringinput1_positive
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

<<<<<<< HEAD

## sad path 2
* greet
  - utter_greet
* mood_sadness
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye
=======
>>>>>>> 8d1750abd62e5329f2bafa6e3bedab4e19c5ee0b

## New Story

* greet
* inform
* mood_surprise

## Generated Story 7896886473463180819
* greet
    - utter_greet
    - utter_ask_howcanhelp
* inform
    - utter_ask_gender
* inform
    - rewind
* inform{"Text": "man"}
    - utter_ask_size
* inform
