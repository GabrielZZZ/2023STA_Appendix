# Example conversations with ChatGPT {#conversation-example}

1.  **User: Give me five metamorphic relations (MRs) for testing the
    parking module of autonomous driving systems (ADSs)**

    **ChatGPT:** Sure, here are five MRs for testing the parking module
    of autonomous driving systems:

    -   MR1: Change in starting position This MR involves changing the
        starting position of the car before parking. The expected
        behavior is that the car should be able to detect the new
        position and park accordingly.

    -   MR2: Change in parking spot size. This MR involves changing the
        size of the parking spot. The expected behavior is that the car
        should be able to adjust its parking maneuver to fit in the new
        spot size.

    -   MR3: Change in parking lot layout. This MR involves changing the
        layout of the parking lot. The expected behavior is that the car
        should be able to detect the changes and adjust its parking
        maneuver accordingly.

    -   MR4: Change in obstacle position. This MR involves changing the
        position of obstacles in the parking lot. The expected behavior
        is that the car should be able to detect the new position of the
        obstacles and park accordingly.

    -   MR5: Change in weather conditions. This MR involves changing the
        weather conditions, such as rain or snow. The expected behavior
        is that the car should be able to adjust its parking maneuver to
        account for the slippery surface or reduced visibility.

2.  **User: You should include the input relations and output relations
    for each MR.**

    **ChatGPT:** Sure! Here are the input relations, output relations,
    and expected behaviors for each of the five MRs I listed previously
    for testing the parking module of autonomous driving systems:

    -   MR1: Change in starting position

        -   Input relation: Starting position of the car

        -   Output relation: Final parking position of the car

        -   Expected behavior: The car should detect the new starting
            position and park accordingly, resulting in a final parking
            position that is appropriate for the new starting position.

    -   MR2: Change in parking spot size

        -   Input relation: Size of the parking spot

        -   Output relation: Final parking position of the car

        -   Expected behavior: The car should adjust its parking
            maneuver to fit in the new spot size, resulting in a final
            parking position that is appropriate for the new spot size.

    -   MR3: Change in parking lot layout

        -   Input relation: Layout of the parking lot

        -   Output relation: Final parking position of the car

        -   Expected behavior: The car should detect the changes in the
            parking lot layout and adjust its parking maneuver
            accordingly, resulting in a final parking position that is
            appropriate for the new layout.

    -   MR4: Change in obstacle position

        -   Input relation: Position of obstacles in the parking lot

        -   Output relation: Final parking position of the car

        -   Expected behavior: The car should detect the new position of
            the obstacles and park accordingly, resulting in a final
            parking position that is appropriate for the new obstacle
            position.

    -   MR5: Change in weather conditions

        -   Input relation: Weather conditions

        -   Output relation: Final parking position of the car

        -   Expected behavior: The car should adjust its parking
            maneuver to account for the slippery surface or reduced
            visibility due to the changed weather conditions, resulting
            in a final parking position that is appropriate for the new
            conditions.

3.  **User: The input relation and output relation for each MR are
    vague. State the changes among inputs and the relations among
    outputs more clearly.**

    **ChatGPT:** Sure! Here are the more specific input relations and
    output relations for each MR for testing the parking module of
    autonomous driving systems:

    -   MR1: Change in starting position

        -   Input relation: The initial position (x,y) of the car before
            parking

        -   Output relation: The final parking position (x',y') of the
            car

        -   Expected behavior: The car should adjust its parking
            maneuver to account for the change in the initial position
            and park accordingly, resulting in a final parking position
            that is appropriate for the new starting position.

    -   MR2: Change in parking spot size

        -   Input relation: The size of the original parking spot
            (length, width)

        -   Output relation: The final parking position (x',y') of the
            car

        -   Expected behavior: The car should adjust its parking
            maneuver to fit in the new spot size, resulting in a final
            parking position that is appropriate for the new spot size.

    -   MR3: Change in parking lot layout

        -   Input relation: The original and new parking lot layouts

        -   Output relation: The final parking position (x',y') of the
            car

        -   Expected behavior: The car should adjust its parking
            maneuver to account for the changes in the parking lot
            layout and park accordingly, resulting in a final parking
            position that is appropriate for the new layout.

    -   MR4: Change in obstacle position

        -   Input relation: The original and new position (x,y) of
            obstacles in the parking lot

        -   Output relation: The final parking position (x',y') of the
            car

        -   Expected behavior: The car should adjust its parking
            maneuver to account for the new position of the obstacles
            and park accordingly, resulting in a final parking position
            that is appropriate for the new obstacle position.

    -   MR5: Change in weather conditions

        -   Input relation: The original and new weather conditions,
            such as rain or snow

        -   Output relation: The final parking position (x',y') of the
            car

        -   Expected behavior: The car should adjust its parking
            maneuver to account for the slippery surface or reduced
            visibility due to the changed weather conditions, resulting
            in a final parking position that is appropriate for the new
            conditions.

4.  **User: the expression "resulting in a final parking position that
    is appropriate for the new conditions.\" is vague. Make it clearer
    for each MR**

    **ChatGPT:** Certainly! Here are the updated expected behaviors for
    each MR that make the final parking position more specific:

    -   MR1: Change in starting position

        -   Expected behavior: The car should adjust its parking
            maneuver to account for the change in the initial position
            and park accordingly, resulting in a final parking position
            that is appropriate for the new starting position. For
            example, if the starting position is closer to the edge of
            the parking lot, the final parking position should be
            adjusted to avoid hitting any objects or pedestrians.

    -   MR2: Change in parking spot size

        -   Expected behavior: The car should adjust its parking
            maneuver to fit in the new spot size, resulting in a final
            parking position that is appropriate for the new spot size.
            For example, if the parking spot is larger, the car should
            park closer to the center of the spot to avoid leaving too
            much space on either side.

    -   MR3: Change in parking lot layout

        -   Expected behavior: The car should adjust its parking
            maneuver to account for the changes in the parking lot
            layout and park accordingly, resulting in a final parking
            position that is appropriate for the new layout. For
            example, if the parking lot layout changes to include
            diagonal parking spaces, the car should adjust its parking
            angle accordingly.

    -   MR4: Change in obstacle position

        -   Expected behavior: The car should adjust its parking
            maneuver to account for the new position of the obstacles
            and park accordingly, resulting in a final parking position
            that is appropriate for the new obstacle position. For
            example, if an obstacle is now positioned closer to the
            parking space, the car should park farther away from the
            obstacle to avoid hitting it.

    -   MR5: Change in weather conditions

        -   Expected behavior: The car should adjust its parking
            maneuver to account for the slippery surface or reduced
            visibility due to the changed weather conditions, resulting
            in a final parking position that is appropriate for the new
            conditions. For example, if the surface is slippery due to
            rain, the car should park more slowly and cautiously to
            avoid slipping or sliding.

5.  **User: You miss the input and output relations**

    **ChatGPT:** I apologize for the confusion. Here are the updated
    input and output relations for each MR, along with the clearer
    expected behaviors:

    -   MR1: Change in starting position

        -   Input relation: Original starting position (x,y) and new
            starting position (x',y')

        -   Output relation: Final parking position (x",y")

        -   Expected behavior: The car should adjust its parking
            maneuver to account for the change in the initial position
            and park accordingly, resulting in a final parking position
            (x",y") that is appropriate for the new starting position.
            For example, if the starting position is closer to the edge
            of the parking lot, the final parking position should be
            adjusted to avoid hitting any objects or pedestrians.

    -   MR2: Change in parking spot size

        -   Input relation: Original parking spot size (length, width)
            and new parking spot size (length', width')

        -   Output relation: Final parking position (x",y")

        -   Expected behavior: The car should adjust its parking
            maneuver to fit in the new spot size, resulting in a final
            parking position (x",y") that is appropriate for the new
            spot size. For example, if the parking spot is larger, the
            car should park closer to the center of the spot to avoid
            leaving too much space on either side.

    -   MR3: Change in parking lot layout

        -   Input relation: Original and new parking lot layouts

        -   Output relation: Final parking position (x",y")

        -   Expected behavior: The car should adjust its parking
            maneuver to account for the changes in the parking lot
            layout and park accordingly, resulting in a final parking
            position (x",y") that is appropriate for the new layout. For
            example, if the parking lot layout changes to include
            diagonal parking spaces, the car should adjust its parking
            angle accordingly.

    -   MR4: Change in obstacle position

        -   Input relation: Original and new position (x,y) of obstacles
            in the parking lot

        -   Output relation: Final parking position (x",y")

        -   Expected behavior: The car should adjust its parking
            maneuver to account for the new position of the obstacles
            and park accordingly, resulting in a final parking position
            (x",y") that is appropriate for the new obstacle position.
            For example, if an obstacle is now positioned closer to the
            parking space, the car should park farther away from the
            obstacle to avoid hitting it.

    -   MR5: Change in weather conditions

        -   Input relation: Original and new weather conditions, such as
            rain or snow

        -   Output relation: Final parking position (x",y")

        -   Expected behavior: The car should adjust its parking
            maneuver to account for the slippery surface or reduced
            visibility due to the changed weather conditions, resulting
            in a final parking position (x",y") that is appropriate for
            the new conditions. For example, if the surface is slippery
            due to rain, the car should park more slowly and cautiously
            to avoid slipping or sliding.

<!-- # The results of using ChatGPT for generating difference number of metamorphic relations

::: table*
   **Metamorphic Relation**  **Description**
  -------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------
             MR1             If the initial parking spot is occupied, the system should identify an alternative parking spot.
             MR2             If the car is facing in the opposite direction of the initial parking spot, the system should perform a U-turn and approach the spot from the correct direction.
             MR3             If there are obstacles in the parking spot, the system should not attempt to park and display a warning message.
             MR4             If the car is moving too fast, the system should not attempt to park and display a warning message.
             MR5             If the car is too close to the car in front or behind, the system should not attempt to park and display a warning message.
             MR6             If the car is too close to the curb or another obstacle, the system should adjust the parking position accordingly.
             MR7             If the car is not centered in the parking spot, the system should adjust the position accordingly.
             MR8             If the parking spot is too small for the car, the system should not attempt to park and display a warning message.
             MR9             If the car is parked too far away from the curb, the system should adjust the position accordingly.
             MR10            If the car is parked too close to the curb, the system should adjust the position accordingly.
             MR11            If the car is parked on a hill, the system should engage the parking brake.
             MR12            If the car is parked on a slope, the system should adjust the position to prevent the car from rolling.
             MR13            If the car is parked on a rough surface, the system should adjust the position to prevent damage to the car.
             MR14            If the car is parked in a tight space, the system should adjust the steering wheel accordingly.
             MR15            If the car is parked on a narrow street, the system should adjust the position accordingly.
             MR16            If the car is parked on a busy street, the system should display a warning message to the driver.
             MR17            If the car is parked in a parallel parking spot, the system should adjust the position accordingly.
             MR18            If the car is parked in a diagonal parking spot, the system should adjust the position accordingly.
             MR19            If the car is parked in a handicapped parking spot, the system should display a message to the driver.
             MR20            If the car is parked in a spot reserved for electric vehicles, the system should display a message to the driver.

[]{#table:parking-mr-long label="table:parking-mr-long"}
::: -->
