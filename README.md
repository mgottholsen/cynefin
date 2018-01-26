# cynefin
Cynefin is a Welsh word meaning haunt, habitat, acquainted, accustomed, familiar. It carries with it a sense of rootedness—temporal, physical, cultural or spiritual. The word is similar in meaning to Heimat in German and has been compared to the Maori word turangawaewae, a place to stand. The idea of the Cynefin framework is that it offers decision-makers a "sense of place" from which to view their perceptions.

## Intent & Objective
This project is intended to automate environment mapping, leveraging consumer grade hardware in conjunction with a proxy API that will field requests to Mapillary, in addition to ALPR, storing imagery in an S3 bucket for potential later processing.

This is for mapping a city with a $130 4K Yi camera, and uploading it to Mapillary which identifies objects in street view photography. Additionally, the imagery will be processed by [OpenALPR](https://github.com/openalpr/openalpr).

### Hardware
Current development platform:

- Yi 4K,  Armbarella processor 

