# Ex.No.9 – Exploration of Prompting Techniques for Video Generation

## Date: 10/09/2026

## Name: Yazhini S

## Register No.: 212223050062
---

# Aim

To demonstrate the ability of text-to-video generation tools to reproduce an existing autonomous-driving video by creating precise and progressively refined prompts. The experiment focuses on analyzing an ADAS/autonomous-driving scene and generating a similar video showing a driverless vehicle navigating a public road safely.

---

# Abstract

Artificial Intelligence and Advanced Driver Assistance Systems (ADAS) are transforming modern transportation by enabling vehicles to perceive their surroundings and perform driving tasks with reduced human intervention. Text-to-video generation provides a way to create realistic simulations of such automotive scenarios using natural-language prompts.

In this experiment, a selected portion of the video **“Tesla Delivers Itself to New Owner”** is used as the reference. The selected portion focuses on a vehicle traveling on a public road without a visible driver while maintaining its lane and navigating surrounding traffic.

The reference scene is analyzed in terms of vehicle movement, road environment, traffic, lighting, camera perspective, and visual style. Basic, refined, and detailed prompts are then created and used to generate a similar AI video.

---

# Introduction

ADAS and autonomous-driving technologies combine cameras, sensors, artificial intelligence, and vehicle-control systems to assist with tasks such as lane keeping, traffic awareness, braking, and navigation.

The selected reference video demonstrates an autonomous vehicle traveling through real-world road conditions without a visible driver. The original video was published by Tesla and describes an autonomous Model Y driving from Gigafactory Texas to its new owner's home, covering parking lots, highways, intersections, and city roads.

For this experiment, only the **ADAS/autonomous-driving portion** is considered. Unrelated portions of the original video are trimmed so that the experiment concentrates on the vehicle driving on the road.

---

# Reference Video

**Title:** Tesla Delivers Itself to New Owner

**Source:** Tesla – YouTube

**Video Link:**  
https://www.youtube.com/watch?v=GU16hXSSGKs


## Selected Content

The selected clip focuses on:

- A vehicle traveling without a visible driver.
- The vehicle moving along a public road.
- Surrounding vehicles and normal traffic conditions.
- The vehicle maintaining its lane.
- Road intersections and traffic signals.
- Daylight outdoor conditions.
- Driverless/autonomous-driving appearance.
- Stable forward-facing camera perspective.

> **Note:** The original video should be trimmed to retain only the relevant autonomous-driving portion before performing the experiment.

---

# AI Tools Required

- ChatGPT / DALL·E for prompt development
- Google Gemini
- Runway
- Pika
- Stable Video Diffusion
- Other available text-to-video generation tools

---

# Selected Video Analysis

## 1. Objects / Subjects

The main subject is a modern electric vehicle traveling on a public road without a visible driver.

Other visible elements include:

- Surrounding cars
- Road lanes
- Traffic signals
- Roadside buildings
- Utility poles
- Sidewalks
- Trees and vegetation
- Vehicle dashboard/interior in some camera views

---

## 2. Colors

The scene mainly contains:

- White and silver vehicles
- Dark vehicle interiors
- Gray asphalt roads
- Green roadside vegetation
- Blue sky
- White clouds
- Black and gray vehicle components

The overall color appearance is natural and realistic.

---

## 3. Lighting

The video is recorded during daylight.

The lighting characteristics include:

- Bright natural sunlight
- Soft shadows
- Clear visibility
- Reflections on vehicle surfaces
- Balanced exposure
- Natural outdoor illumination

---

## 4. Background

The background contains a typical urban/suburban road environment with:

- Multiple lanes
- Other vehicles
- Traffic signals
- Buildings
- Sidewalks
- Utility poles
- Trees and grass
- Elevated road structures

---

## 5. Vehicle Movement

The main vehicle:

- Moves forward along the road.
- Remains within its lane.
- Maintains a controlled speed.
- Travels among other vehicles.
- Approaches intersections and traffic signals.
- Demonstrates autonomous-driving behavior.

---

## 6. Camera Perspective

The selected scene uses a realistic automotive camera perspective.

The camera appears to capture the road from inside or around the vehicle, providing a forward view of:

- Road
- Traffic
- Vehicle surroundings
- Lane markings
- Traffic signals

The perspective gives the viewer the impression of being inside the autonomous vehicle.

---

## 7. Style

The reference is:

**Realistic automotive footage / documentary-style driving video**

It does not use cartoon or cinematic fantasy effects. The objective is to reproduce a believable real-world driving environment.

---

# Procedure

## Step 1 – Select the Reference Video

The video **“Tesla Delivers Itself to New Owner”** was selected as the reference material.

The original video contains autonomous-driving footage of a Tesla Model Y traveling through real-world roads.

---

## Step 2 – Trim the Relevant Section

Only the portion showing the vehicle driving autonomously on the road is selected.

Unnecessary sections such as:

- Vehicle delivery
- Introduction
- Parking-lot scenes
- Owner-related scenes
- Other unrelated footage

are excluded.

The final selected clip focuses on the autonomous-driving sequence.

---

# Step 3 – Analyze the Video

The selected clip was examined based on:

| Feature | Observation |
|---|---|
| Main Subject | Driverless modern electric vehicle |
| Environment | Urban/suburban public road |
| Traffic | Multiple vehicles traveling normally |
| Road | Multi-lane paved road |
| Lighting | Bright natural daylight |
| Sky | Clear blue sky with clouds |
| Background | Buildings, traffic signals, trees and infrastructure |
| Vehicle Motion | Smooth forward movement |
| Driving Behavior | Lane following and controlled navigation |
| Camera | Forward-facing automotive viewpoint |
| Style | Realistic documentary/automotive footage |
| Mood | Calm, safe and technologically advanced |

---

# Step 4 – Create the Basic Prompt

## Prompt 1

> **"A driverless electric car driving on a city road with other vehicles during the daytime."**

### Observation

The basic prompt identifies the main concept of autonomous driving but does not provide sufficient information about the road layout, traffic, camera position, vehicle behavior, lighting, or surroundings.

---

# Step 5 – Refine the Prompt

## Prompt 2

> **"A modern driverless electric car smoothly driving along a multi-lane urban road during daylight, surrounded by normal traffic, with traffic lights, buildings, trees, and clear lane markings visible."**

### Observation

The refined prompt adds:

- Multi-lane road
- Daylight
- Surrounding traffic
- Traffic signals
- Buildings
- Trees
- Lane markings
- Smooth vehicle movement

This creates a more realistic autonomous-driving scenario.

---

# Step 6 – Final Detailed Prompt

## Prompt 3

> **"Create a photorealistic automotive driving video showing a modern electric vehicle traveling autonomously on a multi-lane urban road during a bright sunny day. The vehicle moves smoothly and steadily without a visible driver, maintaining its lane while traveling through normal traffic. Several cars and pickup trucks move naturally in adjacent lanes at realistic speeds. The road contains clear lane markings, traffic signals, intersections, sidewalks, utility poles, roadside grass, trees, and commercial buildings. Show the vehicle approaching and passing through a normal urban intersection while maintaining a safe trajectory. Use a realistic forward-facing camera perspective from inside the vehicle, with the dashboard and windshield subtly visible. Natural daylight, realistic shadows, accurate vehicle proportions, physically correct road motion, stable camera movement, realistic reflections, documentary-style automotive footage, no dramatic effects, no collisions, no sudden movements, and no visible driver."**

---

# Step 7 – Negative Prompt / Accuracy Instructions

The following instructions can be added to reduce unwanted results:

> **"Avoid visible drivers, distorted vehicles, floating cars, unrealistic road geometry, sudden lane changes, collisions, excessive motion blur, duplicated vehicles, warped traffic lights, unrealistic buildings, cartoon graphics, futuristic fantasy elements, camera shaking, and unnatural vehicle movement."**

---

# Step 8 – Generate the Video

The final prompt is entered into a suitable text-to-video generation model such as:

- Runway
- Pika
- Google Gemini/Veo, if available
- Stable Video Diffusion
- Other available AI video-generation platforms

The generated video should be saved for comparison with the reference clip.

---

# Step 9 – Compare the Generated Video

The generated video is compared with the selected reference based on:

- Vehicle appearance
- Driverless appearance
- Road environment
- Vehicle movement
- Traffic
- Lane positioning
- Camera perspective
- Lighting
- Background
- Realism
- Overall visual similarity

---

# Comparison of Original and Generated Video

| Parameter | Original Video | Generated Video |
|---|---|---|
| Main Subject | Autonomous electric vehicle | Autonomous electric vehicle |
| Driver | No visible driver | No visible driver |
| Environment | Public urban/suburban road | Similar urban/suburban road |
| Traffic | Multiple surrounding vehicles | Multiple surrounding vehicles |
| Road | Multi-lane paved road | Multi-lane paved road |
| Vehicle Motion | Smooth forward movement | Smooth forward movement |
| Lane Following | Vehicle maintains road path | Vehicle maintains road path |
| Traffic Signals | Present | Included |
| Lighting | Natural daylight | Natural daylight |
| Camera | Automotive/road-facing view | Forward-facing automotive view |
| Background | Buildings, trees and infrastructure | Similar roadside environment |
| Style | Realistic automotive footage | Photorealistic AI video |

---

# Similarities

The generated video successfully attempts to reproduce the major characteristics of the reference:

1. A modern vehicle is shown driving without a visible driver.
2. The vehicle travels on a public road.
3. Other vehicles are present in surrounding lanes.
4. The vehicle follows a defined road path.
5. Traffic signals and road infrastructure are included.
6. The scene takes place during daylight.
7. The camera provides a realistic automotive perspective.
8. The generated scene follows a realistic automotive-video style.
9. The overall concept of autonomous driving is preserved.

---

# Differences Observed

Some differences may occur between the reference and generated video:

- The exact vehicle model may not be identical.
- Road geometry may differ.
- The number and positions of surrounding vehicles may change.
- Traffic signal positions may vary.
- Buildings and roadside objects may not match exactly.
- Vehicle movements may differ slightly.
- Camera movement may not perfectly match the original.
- Small visual details may be generated differently.

---

# Prompt Refinement

After comparing the first generated output with the reference, the prompt can be improved by adding more specific instructions.

## Initial Prompt

> "A driverless electric car driving on a city road."

## Improved Prompt

> "A modern driverless electric car driving smoothly on a multi-lane urban road with surrounding traffic during daylight."

## Final Prompt

> "A photorealistic automotive driving video showing a modern electric vehicle traveling autonomously on a multi-lane urban road during a bright sunny day, without a visible driver, maintaining its lane among normal traffic, approaching traffic signals and intersections, with realistic road markings, surrounding vehicles, buildings, trees, sidewalks and utility poles, captured from a stable forward-facing interior automotive camera."

## Result of Refinement

Prompt refinement improves the generated video's:

- Scene composition
- Vehicle behavior
- Road environment
- Camera perspective
- Lighting
- Realism
- Autonomous-driving appearance

---

# Prompting Framework Used

The experiment follows a three-stage prompting approach.

## Level 1 – Basic Prompt

Describes only the main subject.

> "A driverless electric car driving on a city road."

---

## Level 2 – Refined Prompt

Adds environmental and movement details.

> "A modern driverless electric car smoothly driving along a multi-lane urban road during daylight, surrounded by normal traffic, with traffic lights, buildings, trees, and clear lane markings visible."

---

## Level 3 – Detailed Prompt

Adds:

- Vehicle behavior
- Road layout
- Traffic
- Camera position
- Lighting
- Background
- Perspective
- Motion
- Realism
- Negative instructions

This produces a closer representation of the reference video.

---

# Observations

1. Basic prompts produce only a general representation of autonomous driving.
2. Adding vehicle behavior improves motion realism.
3. Describing road conditions helps establish a realistic driving environment.
4. Specifying the camera perspective makes the generated video more similar to automotive footage.
5. Describing surrounding traffic improves scene realism.
6. Lighting instructions help reproduce the daytime appearance.
7. Explicitly mentioning the absence of a visible driver helps communicate the autonomous-driving concept.
8. Negative prompts can reduce distorted vehicles and unrealistic movements.
9. Detailed prompts provide better control over the generated scene.
10. Multiple iterations may be required to achieve a close visual match.

---

# Advantages

- Enables rapid creation of autonomous-driving simulations.
- Does not require physical vehicle testing.
- Can be used for educational demonstrations.
- Helps visualize ADAS and autonomous-driving concepts.
- Allows different road conditions to be simulated.
- Prompts can be modified easily.
- Useful for presentations and technology demonstrations.

---

# Limitations

- AI-generated vehicle motion may not always be physically accurate.
- Exact reproduction of the original video is difficult.
- Road markings and traffic signals may sometimes appear distorted.
- Vehicle geometry may change between frames.
- AI-generated videos may contain inconsistent objects.
- Autonomous-driving behavior shown in generated footage should not be treated as proof of real-world vehicle capability.
- Several prompt iterations may be necessary.

---

# Applications

| Application | Description |
|---|---|
| ADAS Education | Demonstrating autonomous-driving concepts to students |
| Automotive Training | Visualizing vehicle-assistance systems |
| Simulation | Creating synthetic driving environments |
| Research | Generating scenarios for AI/vehicle perception studies |
| Presentations | Demonstrating future mobility technologies |
| Virtual Testing | Creating conceptual road scenarios |
| Autonomous Vehicle Development | Visualizing possible driving situations |

---

# Future Scope

Future text-to-video systems can be used to create more sophisticated automotive simulations involving:

- Lane-change scenarios
- Emergency braking situations
- Pedestrian detection
- Traffic-sign recognition
- Obstacle avoidance
- Highway driving
- Night-time driving
- Rain and fog conditions
- Complex intersections
- Vehicle-to-vehicle interaction
- Multi-camera autonomous-driving simulations

Integration with automotive simulation platforms could further improve the realism and usefulness of these generated scenarios.

---

# Deliverables

## 1. Original Video

**Reference:** *Tesla Delivers Itself to New Owner*

**Link:**  
https://www.youtube.com/watch?v=GU16hXSSGKs

---

## 2. Trimmed Part

<img width="1313" height="720" alt="image" src="https://github.com/user-attachments/assets/3328517f-836e-440a-b2b5-13af30546c27" />

---

## 3. Generated Video


https://github.com/user-attachments/assets/3632382f-e2f3-4f86-9c97-0c5ed8712d0e


---

## 4. Prompts Used

### Prompt 1 – Basic

> A driverless electric car driving on a city road with other vehicles during the daytime.

### Prompt 2 – Refined

> A modern driverless electric car smoothly driving along a multi-lane urban road during daylight, surrounded by normal traffic, with traffic lights, buildings, trees, and clear lane markings visible.

### Prompt 3 – Final

> A photorealistic automotive driving video showing a modern electric vehicle traveling autonomously on a multi-lane urban road during a bright sunny day. The vehicle moves smoothly and steadily without a visible driver, maintaining its lane while traveling through normal traffic. Several cars and pickup trucks move naturally in adjacent lanes at realistic speeds. The road contains clear lane markings, traffic signals, intersections, sidewalks, utility poles, roadside grass, trees, and commercial buildings. Show the vehicle approaching and passing through a normal urban intersection while maintaining a safe trajectory. Use a realistic forward-facing camera perspective from inside the vehicle, with the dashboard and windshield subtly visible. Natural daylight, realistic shadows, accurate vehicle proportions, physically correct road motion, stable camera movement, realistic reflections, documentary-style automotive footage, no dramatic effects, no collisions, no sudden movements, and no visible driver.

---

# Result

The selected autonomous-driving portion of the reference video was analyzed and reproduced using progressively refined text prompts. The final prompt generated a realistic autonomous-driving scene containing a driverless electric vehicle, surrounding traffic, road infrastructure, traffic signals, and natural daylight conditions.

---

# Conclusion

The experiment demonstrated the use of **prompt engineering for text-to-video generation** by reproducing an autonomous-driving scenario from an existing reference video. Starting with a basic description and progressively adding details about the vehicle, road, traffic, camera perspective, lighting, movement, and environment improved the similarity of the generated video.

The experiment also demonstrated that **specific descriptions of motion and scene composition are particularly important for video generation**, because the AI model must generate not only individual visual elements but also continuous movement between frames.

Although exact reproduction of the original video is difficult, carefully structured prompts can generate visually similar autonomous-driving simulations. Such techniques can be useful for **ADAS education, automotive visualization, simulation, presentations, and future AI-based driving-system research**.
