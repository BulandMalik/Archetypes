## Quality Attributes Scenarios

Lets start by mapping architecture characteristics (we also referred them as architecture illities or non functional requirements) and see what type of characteristics we could extract out from the core system requirements.

#### **Business Requirements(leftside) <---> Quality Attributes(rightside)**

## *Security*
- 

## *Availability*
- 

## *Scalability*
- 

## *Elasticity*
- Scalability is required for elasticity, but not the other way around.
- The system must quickly and automatically cater to a bust in the incoming requests.

## *Extensibility*
- The level of extensibility reflects how easy it is to extend or enhance the software system. Software systems that are designed to be extensible take future growth into consideration by anticipating the need to add new functionality.
- It also enable our platform to quickly do experiments.
- There are different integration points to this system so it should be easily extendiable for any such future needs (new integration point, new engagement model etc.)

## Performance
- #### *Response time*
    - Customer engaged in different forums or live ongoing welness education classes are few examples where quick response time is very critical. Stream capability specially needs to account for better bandwidth that helps getting responses within agreed upon time limits.
    - Customer interactions must complete timely (within defined SLA, TP99 <700ms for most critical operartions) to provide a smoother customer experience.
    - All non-customer interactions should be responsive enough to support operations, but it’s acceptable to be less responsive than the user/customer interactions.
- #### *Throughput* 
    - During peak hours, the system must be able to support a high number of concurrent user sessions (e.g., 200 simultaneous users). 

## *App usability* 
- The different versions of the app should provide a user experience that appeals to the target user population. 
- Using UX design techniques, and providing high levels of customization are goals.
- AT the end of the day, it should be a seamless experience for Farmacy Foods and Family customers.


Along with this there are some other characteristics that we should in general keep in mind and nopt calling out as they are cionsidered implicit for this system perspective.

### Fault Tolerance


### Configurability

### Reliability
