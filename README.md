# 🎨 Real-Time Color Recognition Using OpenCV

##  Description

This project uses OpenCV to detect and recognize colored objects in real time using a webcam.

The system detects:
- 🔴 Red
- 🟢 Green
- 🔵 Blue
- 🟡 Yellow

The detected object is highlighted with a bounding box, color label, and center coordinates.

---

## 🛠 Tools & Libraries

- Python
- OpenCV
- NumPy
- Jupyter Notebook

---

# Implementation Steps

## 1. Capture Video

- Used OpenCV to access the webcam.
- Captured live frames for processing.

## 2. Convert Color Space

- Converted images from BGR to HSV.
- HSV was used because it makes color detection more accurate under different lighting conditions.

## 3. Detect Colors

- Defined HSV ranges for each color.
- Created masks to isolate the required colors.

## 4. Remove Noise

- Applied morphological operations to improve the masks and remove small unwanted areas.

## 5. Detect Objects

- Used contours to find detected objects.
- Filtered small areas to avoid false detection.
- Added:
  - Bounding boxes
  - Color labels
  - Object center coordinates

---

# Results

The system successfully detected different colored objects in real time.

## Test Cases

### 🔴 Red Detection

![Red Detection](results/red.png)


### 🟢 Green Detection

![Green Detection](results/green.png)


### 🔵 Blue Detection

![Blue Detection](results/blue.png)


### 🟡 Yellow Detection

![Yellow Detection](results/yellow.png)


---

# 👩‍💻 Author

**Nassebah Al-Dubayyan**