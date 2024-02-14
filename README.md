# Car Hub

Using Typescript in Next.js this application is a one stop shop for your car renting services. The web application uses [Cars by API-Ninjas](https://rapidapi.com/apininjas/api/cars-by-api-ninjas) to get information on the cars that include: make, model, year, mpg, fuel type and drive type. Also, to generate images of the cars this application also uses [Imagin Studio API](https://www.imagin.studio/car-image-api). 


## Features

- Search Bar funtionality
- Filter Cars by Fuel Type and Year
- Open Model to show more car details and pictures


## Demo

You can test it out [here](https://car-hub-beige.vercel.app/)
<img width="1468" alt="Screen Shot 2023-06-17 at 2 23 08 AM" src="https://github.com/ParasK02/Car-Hub/assets/90861109/a4f99fbb-c002-4e1f-990f-55df1692cc39">



## Notes
There is a bug with the current version of Next.js version 13.2.5, where the search functionality resets the screen position. So after a request using the search bar, filters or the show more button the data is loaded however, the screen is reset back to the top. 




