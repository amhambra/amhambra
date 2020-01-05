gradle run --warning-mode all

Sample Output:

C:\Users\schulte\git\amhambra\projects\littlecontact>gradle run --warning-mode all

> Task :run
Jan 05, 2020 11:30:27 PM com.google.api.client.util.store.FileDataStoreFactory setPermissionsToOwnerOnly
WARNUNG: unable to change permissions for everybody: C:\Users\schulte\git\amhambra\projects\littlecontact\tokens
Jan 05, 2020 11:30:27 PM com.google.api.client.util.store.FileDataStoreFactory setPermissionsToOwnerOnly
WARNUNG: unable to change permissions for owner: C:\Users\schulte\git\amhambra\projects\littlecontact\tokens
Name: TEST UserTest
    : {"emailAddresses":[{"formattedType":"Home","metadata":{"primary":true,"source":{"id":"77d2e7500a9468b4","type":"CONTACT"}},"type":"home","value":"unknown@fschulte.net"}],"etag":"%EgcBAj0JPjcuGgQBAgUHIgxhRkZaRURDTjgwVT0=","names":[{"displayName":"TEST UserTest","displayNameLastFirst":"UserTest, TEST","familyName":"UserTest","givenName":"TEST","metadata":{"primary":true,"source":{"id":"77d2e7500a9468b4","type":"CONTACT"}}}],"resourceName":"people/c8634217766583560372"}
Name: Frank Schulte
    : {"emailAddresses":[{"formattedType":"Work","metadata":{"primary":true,"source":{"id":"6bec77508d5cf6cf","type":"CONTACT"}},"type":"work","value":"fschulte.de.dev@gmail.com"}],"etag":"%EgcBAj0JPjcuGgQBAgUHIgxTMnhoaFBlWnZEWT0=","names":[{"displayName":"Frank Schulte","displayNameLastFirst":"Schulte, Frank","familyName":"Schulte","givenName":"Frank","metadata":{"primary":true,"source":{"id":"6bec77508d5cf6cf","type":"CONTACT"}}}],"resourceName":"people/c7776721844414772943"}

BUILD SUCCESSFUL in 5s
3 actionable tasks: 2 executed, 1 up-to-date
C:\Users\schulte\git\amhambra\projects\littlecontact>gradle clean

BUILD SUCCESSFUL in 2s
1 actionable task: 1 executed
C:\Users\schulte\git\amhambra\projects\littlecontact>gradle run --warning-mode all                                                                          
