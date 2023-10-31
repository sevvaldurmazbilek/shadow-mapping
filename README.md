# About

Today, shadow maps can be used for many purposes. Especially with the increasing temperatures in the summer, they allow to have a more comfortable experience in outdoor spaces by showing pedestrians the shaded way to walk or shaded areas. They are also important data for urban planners and policy makers to contribute to the planning of solor panels, for example. Shadow maps are also used in many game engine applications to provide a more realistic game experience. In particular, real-time maps present the current shadow situation in local time at the desired geographical location using the position of the sun calculated with parameters such as sun angle, altitude, elavation. Thus, the maps show the current situation at the time of the search, without the user having to enter any time interval. Since the creation of shadow maps is based on a physical model, it is necessary to use 3D models of buildings according to various features and levels of detail, is a significant data source for these applications. These models, which usually appear as 3 different levels of detail, are names as LoD1, LoD2, LoD3 and ranged from low detail to high detail, respectively. LoD2 models in particular are the most preffered level of detail in such applications, both because they contain enough detail to ensure that the shadow created by the building is close to reality and because they do not carry the details that LoD2 has but do not have any effect on the shadows. In this context, a real-time shadow map has been created for this project using LoD2 data. Shadow maps are automatically calculated and continuously updated according to the geographical location specified.

# Application 

* Real-time shadow mapping with Sun Script
* Control panels to manipulate the date and sky in the background
* See the changes on the shadows by exploring the different dates/time
* Shadow extraction panel on the left top




# Licensing Sun Script
The code for solar orientation calculation is based on the code of the Solar
Calculator developed at the National Oceanic & Atmospheric Administration of the
U.S. Department of Commerce, and is public domain.

The three.js JavaScript 3D library is released under the MIT license. Please see
the official repository of three.js for more details.

