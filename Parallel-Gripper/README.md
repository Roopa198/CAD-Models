# Modular Parallel Jaw Gripper

A compact robotic gripper mechanism designed in Autodesk Fusion 360 for grasping and handling objects of varying shapes and sizes.

The design focuses on a simple mechanical actuation system, modular gripping surfaces, and a compact structure suitable for integration with robotic arms or mobile manipulation platforms.

---

## 📌 Project Overview

This project is a mechanical CAD design of a two-jaw robotic gripper.

The gripper uses a geared actuation mechanism to drive the jaws through a linkage system, allowing both jaws to move toward and away from the center of the gripper.

The curved gripping surfaces are designed to provide better contact with cylindrical and irregularly shaped objects.

The entire mechanism was designed from scratch in **Autodesk Fusion 360**.

---

## 🎯 Design Goals

- Create a compact robotic gripping mechanism
- Provide controlled opening and closing of the jaws
- Accommodate objects of different shapes and sizes
- Maintain a rigid and compact structure
- Allow integration with a motor/actuator
- Keep the design modular for future modifications
- Create a CAD model suitable for further prototyping

---

## ⚙️ Working Principle

The gripper uses a rotational input to actuate the gripping mechanism.

The input gear transfers motion to the internal gear mechanism, which drives the linkage connected to the two jaws.

As the actuator rotates in one direction:

**Actuator → Gear → Linkage → Jaws close**

When the actuator rotates in the opposite direction:

**Actuator → Gear → Linkage → Jaws open**

The linkage arrangement allows the two gripping arms to move symmetrically toward the object.

---

## 🧩 Main Components

The assembly consists of:

- Main mounting plate
- Lower mounting plate
- Actuation gear
- Gear teeth / rack interface
- Left gripping arm
- Right gripping arm
- Linkage arms
- Pivot joints
- Gripping surfaces
- Fastener locations
- Actuator mounting interface

---

## 🛠️ Software Used

| Software | Purpose |
|---|---|
| Autodesk Fusion 360 | 3D CAD modelling and assembly |
| Fusion 360 Joints | Mechanism and motion testing |
| Fusion 360 Drawing | Engineering documentation |
| GitHub | Project documentation and version control |

---

## 🔧 CAD Techniques Used

The design involved:

- Parametric sketching
- Extrusion
- Fillets and chamfers
- Mirror features
- Pattern features
- Construction geometry
- Assembly modelling
- Mechanical joints
- Interference checking
- Component positioning
- Motion testing
- Exploded assembly preparation

---

## 📐 Design Considerations

Several mechanical factors were considered during the design:

### 1. Gripping Geometry

The curved gripping surfaces provide a larger contact area for cylindrical and irregular objects.

### 2. Linkage Motion

The linkage geometry was designed to convert the actuator's rotational motion into the required jaw movement.

### 3. Compactness

The actuation mechanism and mounting structure were kept relatively compact so the gripper can potentially be integrated onto a robotic arm.

### 4. Modularity

The gripping surfaces can be modified or replaced depending on the object being handled.

### 5. Mounting

Multiple mounting points are provided on the main plate for attachment to a robotic system or actuator assembly.

---

## 🖼️ Assembly

![Gripper Assembly](images/gripper_assembly.png)

---

## 🔄 Mechanism

The general motion sequence is:

```text
             ACTUATOR
                 │
                 ▼
          ┌─────────────┐
          │    GEAR     │
          └──────┬──────┘
                 │
                 ▼
            LINKAGE
            /      \
           /        \
          ▼          ▼
      LEFT JAW    RIGHT JAW
           \        /
            \      /
             OBJECT
