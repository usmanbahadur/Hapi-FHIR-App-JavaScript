# Hapi-FHIR-App-JavaScript
FHIR App compatible with latest FHIR release R4 


This FHIR App works against the public Hapi FHIR Server which is an un-authorised server and no OAuth is implemented.  
Hapi FHIR server provides a nearly complete implementation of the FHIR Specification using a 100% open source software stack.
It is hosted by University Health Network.  https://hapi.fhir.org/home?serverId=home_r4&pretty=true 
The app currently shows patient's demographics resource, further resources can be pulled from resource server to expand patient profile.
       
       var client = jqFhir({ baseUrl: 'https://hapi.fhir.org//baseR4' }),
        patientId = '6409';
    
       //http://hapi.fhir.org/baseR4/Observation/6547
       //http://hapi.fhir.org/baseR4/Encounter/6516
