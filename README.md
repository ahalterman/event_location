# event_location

Accompanying materials for "Geolocating Political Events in Text."

## Data

The data consists of text, with canonical tokenization, along with information
on the locations of verbs and, if applicable, their locations. If multiple
verbs are annotated within a sentence, they will appear in separate entries.
Gold standard annotations are marked `source: 'RELABEL'`.

```
{'_id': 'APW_ENG_20030610.0060_2_capture',
 'annotator': 'RA',
 'source': 'APW_RA',
 'spans': [{'end': 15,
   'label': 'VERB',
   'start': 7,
   'text': 'captured',
   'token_end': 1,
   'token_start': 1},
  {'end': 166,
   'label': 'LOCATION',
   'start': 154,
   'text': 'Kodori Gorge',
   'token_end': 28,
   'token_start': 27}],
 'text': 'Gunmen captured two Germans, a Dane and a Georgian translator working for a U.N. military observation team in a Georgian-controlled district of the tense Kodori Gorge on Thursday.',
 'tokens': [{'end': 6, 'id': 0, 'start': 0, 'text': 'Gunmen'},
  {'end': 15, 'id': 1, 'start': 7, 'text': 'captured'},
  {'end': 19, 'id': 2, 'start': 16, 'text': 'two'},
  {'end': 27, 'id': 3, 'start': 20, 'text': 'Germans'},
  {'end': 28, 'id': 4, 'start': 27, 'text': ','},
  {'end': 30, 'id': 5, 'start': 29, 'text': 'a'},
  {'end': 35, 'id': 6, 'start': 31, 'text': 'Dane'},
  {'end': 39, 'id': 7, 'start': 36, 'text': 'and'},
  {'end': 41, 'id': 8, 'start': 40, 'text': 'a'},
  {'end': 50, 'id': 9, 'start': 42, 'text': 'Georgian'},
  {'end': 61, 'id': 10, 'start': 51, 'text': 'translator'},
  {'end': 69, 'id': 11, 'start': 62, 'text': 'working'},
  {'end': 73, 'id': 12, 'start': 70, 'text': 'for'},
  {'end': 75, 'id': 13, 'start': 74, 'text': 'a'},
  {'end': 80, 'id': 14, 'start': 76, 'text': 'U.N.'},
  {'end': 89, 'id': 15, 'start': 81, 'text': 'military'},
  {'end': 101, 'id': 16, 'start': 90, 'text': 'observation'},
  {'end': 106, 'id': 17, 'start': 102, 'text': 'team'},
  {'end': 109, 'id': 18, 'start': 107, 'text': 'in'},
  {'end': 111, 'id': 19, 'start': 110, 'text': 'a'},
  {'end': 120, 'id': 20, 'start': 112, 'text': 'Georgian'},
  {'end': 121, 'id': 21, 'start': 120, 'text': '-'},
  {'end': 131, 'id': 22, 'start': 121, 'text': 'controlled'},
  {'end': 140, 'id': 23, 'start': 132, 'text': 'district'},
  {'end': 143, 'id': 24, 'start': 141, 'text': 'of'},
  {'end': 147, 'id': 25, 'start': 144, 'text': 'the'},
  {'end': 153, 'id': 26, 'start': 148, 'text': 'tense'},
  {'end': 160, 'id': 27, 'start': 154, 'text': 'Kodori'},
  {'end': 166, 'id': 28, 'start': 161, 'text': 'Gorge'},
  {'end': 169, 'id': 29, 'start': 167, 'text': 'on'},
  {'end': 178, 'id': 30, 'start': 170, 'text': 'Thursday'},
  {'end': 179, 'id': 31, 'start': 178, 'text': '.'}]}
  ```
