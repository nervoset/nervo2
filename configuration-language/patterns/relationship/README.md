### Relationships
It seems that ChatGPT understands the relationship between provided entities.
By providing a json with entities and [their relationships](direct-relationships.json) and asking the model
to generate a DOT diagram accordingly:
 - the model is able to generate a correct diagram:
   
   ![DOT diagram](https://www.plantuml.com/plantuml/png/SoWkIImgAStDuKh9J2zABCXGS5Uevb80WaI5w9p4fDGSMoNNl9BCaae5HmKDGqsbM6kmR1Awh9E2XX5SDWLTrWMermmkdOqkxQsWOMOEbyv0b_PGqB2qj8JBbw3BXm1DXrWETRckdKAIDOAT0PL80N6ohH7i4gX41aG2mIv1OYSXiLEikMgv75BpKe0X1W00)
 
 - the model understands which entity has reference to which entity
 - it seems that model understands [transitive relationships](transitive-relationships.json) as well
