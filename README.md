| **HTTP Verb** |         **URL**         | **Request body** |           **Action**           |
|:-------------:|:-----------------------:|:----------------:|:------------------------------:|
| POST          | /activities             |       JSON       | Creates a new activity         |
| GET           | /activities             |      (empty)     | Returns all the activities     |
| GET           | /activities/:activityId |      (empty)     | Returns the specified activity |
| PUT           | /activities/:activityId |       JSON       | Edits the specified activity   |
| DELETE        | /activities/:activityId |      (empty)     | Deletes the specified activity |