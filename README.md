# Entity-Relationalship-Diagram

The customer and the admin are the two parties who are allowed to have access to the database of the system and have diffrent view level schemas' to the database infromation.

Thr customer can make a fresh reservation and book one or at max 2 tickets. He can also see trains b/w staions, check seat availability and get the fare details.

The admin can login only by using master password. He can add station, train, route. 

The system's security has been kept into consideration as well. The database of the system cannot be accessed by any user withhout being authenticated by correct username and password. In case of forgotten password he can recover it by answering the security question which he sets while registering.

This project is designed in such a way that it tackels the problem of data redundancy and reduce the storage.
