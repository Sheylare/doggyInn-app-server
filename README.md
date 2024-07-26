# Doggy Inn


This repository is a [json-server](https://github.com/Sheylare/doggyInn-app-server) created to feed data into the React Application below.


#### [Client Repo here](https://github.com/Sheylare/doggyInn-app-client)


# Server Structure


## Collections


### hosts


```javascript

{

  id,

  name,

  description,

  city,

  address,

  email,

  phone,

  price,

}

```


### reservations


```javascript

 {

   dates,

   quantityDogs,

   dogName,

   dogSize,

   dogAge,

   dogAllergies,

   ownFood,

   additionalNotes,

   ownersName,

   email,

   phone,

   hostId,

   id,


 }

```


## Used API Endpoints in the App


| HTTP Method | URL                         | Request Body                 | Description                                                    |

| ----------- | --------------------------- | ---------------------------- | -------------------------------------------------------------- |

| GET         | `/hosts`                    |                              | Sends all hosts                                                |

| POST        | `/hosts`                    | { name, city, address, description, email, phone,price,}         | Creates a new host                                             |

| GET         | `/hosts/:hostId`            |                              | Sends all details of a host                                    |

|           

| GET         | `/reservations`                  |                              | Sends all reservations                                              

| POST        | `/reservations`                  | {dates, quantityDogs, dogName, dogSize, dogAge, dogAllergies, ownFood, additionalNotes, ownersName, email, phone, hostId, id  }               | Creates a new reservation                                           

| PATCH       | `/reservations`                | {dates, quantityDogs, dogName, dogSize, dogAge, dogAllergies, ownFood, additionalNotes, ownersName, email, phone}               | Edits a reservation                                                 

| DELETE      | `/reservations/:reservationId`            |                              | Deletes a reservation object 

|


 

## Links



### Collaborators


[Marcos Cardoza](https://github.com/Marcocar97)


[Michelle Sredni](https://github.com/michsredni)


[Sheyla Arellano](https://github.com/Sheylare)


### Project


[Repository Link Client](https://github.com/Sheylare/doggyInn-app-client/tree/master)


[Repository Link Server](https://github.com/Sheylare/doggyInn-app-server/tree/master)


[Deploy Link](https://doggy-inn.netlify.app/)


### Slides


[Slides Link](https://shorturl.at/yh2m9)

