## search happy
* greet
  - utter_greet
* search_result{"type_of:search", "name_of_song:here with me"}
  - action_search
* thanks
  - utter_goodbye

## search sad
* greet
  - utter_greet
* search_result{"type_of:search"}
  - utter_ask_name
* name_song{"here with me"}
  - action_search
* thanks
- utter_goodbye

## download happy
* greet
  - utter_greet
* search_result{"type_of:download", "name_of_song:here with me"}
  - action_download
* thanks
  - utter_goodbye

## download sad
* greet
  - utter_greet
* search_result{"type_of:download"}
  - utter_ask_name
* name_song{"here with me"}
  - action_download
* thanks
  - utter_goodbye

## play happy
* greet
  - utter_greet
* search_result{"type_of:play", "name_of_song:here with me"}
  - action_play
* thanks
  - utter_goodbye

## play sad
* greet
  - utter_greet
* search_result{"type_of:play"}
  - utter_ask_name
* name_song{"here with me"}
  - action_play
* thanks
  - utter_goodbye
