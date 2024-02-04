
# Quiz Hero - Admission Quiz

An e-learning platform in which student can give unlimited model test exam and live quiz exam.And see the progress of every subject,every chapter.


## Screenshots


![](https://user-images.githubusercontent.com/53580076/221098427-831c6d77-f9ac-47de-9dc9-e472737c725f.png)


![](https://user-images.githubusercontent.com/53580076/221098394-39eb86aa-6cff-4043-a21d-83a8202475d4.png)
## Features

- Unlimited Model Test
- Live Quiz
- Leaderboard of all user
- Progress of all subject and chapter


## Technical Overview

### Client Side
- Use Kotlin and XML
- Use Retrofit,Dagger-Hilt,Coroutine,Livedata for network call
- Using android Jetpack library
- Single activity  architecture with MVVM and navigation component
- Separate common code.All nececessary code for fragment is placed on a base fragment and extend by all fragment
- Some optimization: Optimize recyclerview using DiffUtil and ListAdapter.Replace nested recyclerview by convert the       nested list to a single list using inheritance and multiple ViewType
- Seperate common design in xml layout for reduce boilerplate code
- Handle error for api call in only one time using safeApiCall.Create a baseViewModel and extend by all viewmodel for handle defult error from server
- Integrate websocket by OkHttp3 library 
- Manage version control with git & github
- Full responsive user interface

### Server Side
- Node js
- express js
- Mongo DB
- Django
- Redis


## Playstore Download link
https://play.google.com/store/apps/details?id=ltd.tinkers.quizhero
