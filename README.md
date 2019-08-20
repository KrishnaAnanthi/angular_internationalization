# angular_internationalization
Multi language support in angular

**To generate i18n files:**

``` npm run int:extract  ```

**To run application in english :**

```	npm run start	```

![English text](https://github.com/KrishnaAnanthi/angular_internationalization/blob/master/English.PNG)

**To run application in french :**

```	npm run start:fr	```

![French text](https://github.com/KrishnaAnanthi/angular_internationalization/blob/master/germen.PNG)

**To run application in Germen :**

```	npm run start:de 	```

![Germen text](https://github.com/KrishnaAnanthi/angular_internationalization/blob/master/french.PNG)

**To add new text**

Add the text in app.component.html file with new id, then run 

``` npm run int:extract  ```

now new text is added to messages.xlf files. Now copy the trans-unit block for new text and paste it in messages.de.xlf and messages.fr.xlf files. Now add the translated lines under target. eg)<target>Bonjour Ananthi</target>
