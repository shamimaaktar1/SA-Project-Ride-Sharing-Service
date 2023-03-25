

<h2 align="center">Ride sharing service</h2>


<p align="left">
 Ride-sharing is an innovative on-demand transport service that aims to promote sustainable transport, reduce car utilization, increase vehicle occupancy, and increase public transport ridership. When it comes to getting about in cities, many people choose ride-sharing apps like Uber or Lyft. Indeed, such apps make short-range commute very easy by offering competitive pricing, reasonably short wait time, high security and high availability. From a technical point of view, systems like these are very interesting because nearest-neighbor searching is hard.  We developed a taxi-sharing system that accepts taxi passengers. These systems have much more complex architecture and there are a lot of components joined together internally to provide riding services all over the world. A user can request a ride through the application and within a few minutes, a driver arrives nearby his/her location to take them to their destination. It has a backend service, a frontend service, and a single database. Passenger requests are sent from smartphones, and ridesharing apps schedule proper taxis to pick them up, subject to time, capacity, and monetary constraints. Indeed, such apps make short-range commutes very easy by offering competitive pricing, a reasonably short wait time, high security, and high availability. From a technical point of view, systems like these are very interesting because nearest-neighbor searching is hard. These systems have a much more complex architecture, and there are a lot of components joined together internally to provide transportation services all over the world.
</p>
<br>

## Contents

- [1. Business goals](#business_goals)



### 1. Business goals
a)To achieve 99.99% reliability of the core travel experience on ride sharing service (only have a total of one hour of downtime per year, and a maximum of one minute per week, in other words, every 10,000 operations can only fail 1 time at a time.

b)Codebase divided by 2: Core code, and optional code. Core code is compulsory when the rider register, calls and completes or cancels travel requirements. Any modification to the core code must go through a rigorous review process. Optional code is less reviewed and can be dynamically closed at any time. This encourages mutual independence at the code level, allowing us to try new features and stop them at any time.

c)Core architecture: class names, inheritance relationships between business logic units (inheritance relationship between business logic units), main business logic, plugin point (name, dependency, structure, etc.), reactive programming chains (relationship between reactive programming), unified platform components (unified platform-level modules).



