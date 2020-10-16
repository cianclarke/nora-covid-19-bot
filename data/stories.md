## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

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

## bot challenge
* bot_challenge
  - utter_iamabot

## faq distancing
* faq_distancing 
  - utter_faq_distancing

## more faq distancing
* greet
  - utter_greet
* faq_distancing 
  - action_faq_distancing

## faq spread happy
* faq_spread
  - utter_faq_spread
  - utter_did_that_help
* affirm
  - utter_happy

## faq spread sad
* faq_spread
  - action_faq_spread
  - utter_did_that_help
* deny
  - utter_sad

## faq symptoms happy
* faq_symptoms
  - utter_symptoms
  - utter_did_that_help
* affirm
  - utter_happy

## faq symptoms sad
* faq_symptoms
  - action_faq_symptoms
  - utter_did_that_help
* deny
  - utter_sad

## faq status
* faq_status
  - action_faq_status


## more faq status
* greet
  - utter_greet
* faq_status
  - action_faq_status
