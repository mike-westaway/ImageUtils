https://docs.microsoft.com/en-gb/azure/cognitive-services/computer-vision/quickstarts/csharp#text-recognition-with-computer-vision-api-using-c-a-namerecognizetext-a

The resolution of the image will significantly affect the accuracy of character recognition.

Example output when the image is reduced by a factor of 4.

{
   "status": "Succeeded",
   "recognitionResult": {
      "lines": [
         {
            "boundingBox": [
               93,
               63,
               118,
               67,
               115,
               88,
               89,
               83
            ],
            "text": "65",
            "words": [
               {
                  "boundingBox": [
                     92,
                     67,
                     117,
                     67,
                     118,
                     85,
                     93,
                     85
                  ],
                  "text": "65"
               }
            ]
         },
         {
            "boundingBox": [
               78,
               124,
               95,
               127,
               93,
               137,
               76,
               134
            ],
            "text": "12",
            "words": [
               {
                  "boundingBox": [
                     78,
                     127,
                     94,
                     127,
                     94,
                     136,
                     78,
                     136
                  ],
                  "text": "12"
               }
            ]
         }
      ]
   }
}