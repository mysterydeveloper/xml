###### Data Representation and Querying - Exercise 6
# eXtensible Markup Language
In this exercise we will look at the syntax and use of eXtensible Markup Language (XML).

## Exercises
Save each exercise as a separate source file.
    
1. The following is an example of a car represented in XML. Copy the XML into a file called cars.xml, and add two more doors: a left rear door and a right rear door.

    ```xml
    <?xml version="1.0" encoding="UTF-8"?>
    <car>
      <registration>152-G-123</registration>
      <make>Ford</make>
      <model>Fiesta</model>
      <colour>Red</colour>
      <doors>
        <door>Driver</door>
        <door>Right passenger</door>
      </doors>
    </car>
    ```

1. On paper, draw the tree structure of the XML from step 1.

1. Wrap the XML in cars.xml in a <cars> tag, and add a second car. Pick your own values for the resistration, make, model and colour of the second car.

1. Add a dealer element to each of the cars, and set the first one to Cars&Co, and the second one to Steve's Cars. Use entity references to correct the syntax.

1. Add an attribute called driveside to each car, setting the first one to "Left" and the second one to "Right".

1. Add an id attribute to each car and set them to the integers 1 and 2 respectively.

1. Create a third car in car.xml, with the following information:

    ID | 3
    ---|----
    driveside|Left
    make|Toyota
    model|Yaris
    colour|grey
    registration|07-TS-127
    doors|Driver;Right passenger;Boot

1. Convert the following JSON into valid XML.

    ```json
    {
      "by" : "dhouston",
      "descendants" : 71,
      "id" : 8863,
      "kids" : [ 8952, 9224, 8917, 8884, 8887, 8943, 8869, 8958, 9005, 9671, 8940, 9067, 8908, 9055, 8865, 8881, 8872, 8873, 8955, 10403, 8903, 8928, 9125, 8998, 8901, 8902, 8907, 8894, 8878, 8870, 8980, 8934, 8876 ],
      "score" : 111,
      "time" : 1175714200,
      "title" : "My YC app: Dropbox - Throw away your USB drive",
      "type" : "story",
      "url" : "http://www.getdropbox.com/u/2/screencast.html"
    }
    ```

## Advanced exercises

1. Write a HTML file that performs an AJAX call to retreive cars.xml, and display it in an HTML table.

## Notes

- [XML tutorial on w3schools.com](http://www.w3schools.com/xml/default.asp)

- [tutorialspoint XML tutorial](http://www.tutorialspoint.com/xml/index.htm)

- [MDN: Document Object Model](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model)

