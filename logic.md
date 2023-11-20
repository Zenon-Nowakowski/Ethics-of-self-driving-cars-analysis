# Visual Objects (mobile) 
Define visual objects, create child objects for: human, animal, and car.
# Visual Objects (static) 
Define static objects, and create child objects for buildings, barriers, and other static objects.
# satellite Data
Pull in satellite data and utilize A* search for pathing. Pull in data about traffic signals and signs. 
# Logic
Create logic to ensure that the car is always moving forward, ignores all data from provided by satellite and sensosrs unless it were to impede its goal. For instance if a pedestrian is spotted the car will run them over as the average pedestrian could not cause the car to stop moving. If the car however detected a stopped vehicle in front it will also stop as the other car could cause series damage to the vehicle preventing it from continuing. 