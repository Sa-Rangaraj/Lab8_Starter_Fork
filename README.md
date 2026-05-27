# Lab8-Starter

[Website](https://sa-rangaraj.github.io/Lab8_Starter_Fork/)

### How are graceful degradation and service workers related?  

Service workers and graceful degredation are related because service workers allow us to implement graceful degredation for the users when faced with network problems. Graceful emphasizes ensuring that "lower levels" of technology do not break the entire system. Rather, certain specific features may fail to function, or function at a lower quality or scope than they did previously. There is impact to the user experience, but the impact is a lessened experience, rather than a complete lack of usability. Service workers allow us to implement this lessened experience for systems that rely on a network connection, when users have the "lesser technology" of a lack of network connection. By storing previous requests and their corresponding responces, the system can mimic a previous internet call through utilizing the stored data. As a result, even when internet access isn't available, the user is still able to use some features that realied on an internet connection, so long as the desired request was made previously. This is a form of graceful degredation, as only new network requests are non-functional, rather than all network requests not working. 
