## search happy
* greet
  - utter_greet
* search_song{"type_of:search", "name_of_song:here with me"}
  - action_search
* thanks
  - utter_goodbye

## search sad
* greet
  - utter_greet
* search_song{"type_of:search"}
  - utter_ask_name
* name_song{"here with me"}
  - action_search
* thanks
- utter_goodbye

## download happy
* greet
  - utter_greet
* download_song{"type_of:download", "name_of_song:here with me"}
  - action_download
* thanks
  - utter_goodbye

## download sad
* greet
  - utter_greet
* download_song{"type_of:download"}
  - utter_ask_name
* name_song{"here with me"}
  - action_download
* thanks
  - utter_goodbye

## play happy
* greet
  - utter_greet
* play_song{"type_of:play", "name_of_song:here with me"}
  - action_play
* thanks
  - utter_goodbye

## play sad
* greet
  - utter_greet
* play_song{"type_of:play"}
  - utter_ask_name
* name_song{"here with me"}
  - action_play
* thanks
  - utter_goodbye
