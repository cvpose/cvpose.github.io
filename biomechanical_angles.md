
| Named Angle                | Label                         | Biomechanical Definition                            | Triplet `(p1, pivot, p2)`                           | Best Planes     |
|---------------------------|-------------------------------|------------------------------------------------------|-----------------------------------------------------|-----------------|
| `NECK`                    | Neck Alignment                | Neck alignment (head vs torso)                      | `NOSE`, `MIDDLE_SHOULDER`, `THORAX`                 | `3D`, `YZ`      |
| `HEAD_TILT`               | Head Tilt                     | Lateral head tilt from shoulder symmetry            | `LEFT_SHOULDER`, `NOSE`, `RIGHT_SHOULDER`           | `XY`            |
| `LEFT_SHOULDER_FLEXION`   | Left Shoulder Flexion         | Flexion/extension of left shoulder                  | `THORAX`, `LEFT_SHOULDER`, `LEFT_ELBOW`             | `3D`, `YZ`      |
| `RIGHT_SHOULDER_FLEXION`  | Right Shoulder Flexion        | Flexion/extension of right shoulder                 | `THORAX`, `RIGHT_SHOULDER`, `RIGHT_ELBOW`           | `3D`, `YZ`      |
| `LEFT_ELBOW_EXTENSION`    | Left Elbow Extension          | Extension/flexion of left elbow                     | `LEFT_SHOULDER`, `LEFT_ELBOW`, `LEFT_WRIST`         | `3D`, `YZ`      |
| `RIGHT_ELBOW_EXTENSION`   | Right Elbow Extension         | Extension/flexion of right elbow                    | `RIGHT_SHOULDER`, `RIGHT_ELBOW`, `RIGHT_WRIST`      | `3D`, `YZ`      |
| `LEFT_WRIST_ROTATION`     | Left Wrist Flexion            | Forearm-hand alignment (approx. wrist flexion)      | `LEFT_ELBOW`, `LEFT_WRIST`, `LEFT_INDEX`            | `3D`, `XY`      |
| `RIGHT_WRIST_ROTATION`    | Right Wrist Flexion           | Forearm-hand alignment (approx. wrist flexion)      | `RIGHT_ELBOW`, `RIGHT_WRIST`, `RIGHT_INDEX`         | `3D`, `XY`      |
| `LEFT_HIP_FLEXION`        | Left Hip Flexion              | Flexion/extension of left hip                       | `THORAX`, `LEFT_HIP`, `LEFT_KNEE`                   | `3D`, `YZ`      |
| `RIGHT_HIP_FLEXION`       | Right Hip Flexion             | Flexion/extension of right hip                      | `THORAX`, `RIGHT_HIP`, `RIGHT_KNEE`                 | `3D`, `YZ`      |
| `LEFT_KNEE_FLEXION`       | Left Knee Flexion             | Knee bend of left leg                               | `LEFT_HIP`, `LEFT_KNEE`, `LEFT_ANKLE`               | `3D`, `YZ`      |
| `RIGHT_KNEE_FLEXION`      | Right Knee Flexion            | Knee bend of right leg                              | `RIGHT_HIP`, `RIGHT_KNEE`, `RIGHT_ANKLE`            | `3D`, `YZ`      |
| `LEFT_ANKLE_FLEXION`      | Left Ankle Flexion            | Foot flexion relative to leg (left)                 | `LEFT_KNEE`, `LEFT_ANKLE`, `LEFT_FOOT_INDEX`        | `3D`, `YZ`      |
| `RIGHT_ANKLE_FLEXION`     | Right Ankle Flexion           | Foot flexion relative to leg (right)                | `RIGHT_KNEE`, `RIGHT_ANKLE`, `RIGHT_FOOT_INDEX`     | `3D`, `YZ`      |
| `SPINAL_CURVATURE`        | Spinal Curvature              | Spine curvature (thoracic/lumbar alignment)         | `MIDDLE_HIP`, `THORAX`, `NECK`                      | `3D`, `YZ`      |
| `TORSO_LEANING`           | Torso Lean                    | Trunk forward/backward inclination                  | `NECK`, `THORAX`, `MIDDLE_HIP`                      | `3D`, `YZ`      |
| `SHOULDER_ELEVATION`      | Shoulder Elevation            | Shoulder imbalance detection                        | `LEFT_SHOULDER`, `MIDDLE_SHOULDER`, `RIGHT_SHOULDER`| `XY`            |
| `HIP_ABDUCTION`           | Hip Abduction (Left)          | Lateral opening of the left leg                     | `MIDDLE_SHOULDER`, `LEFT_HIP`, `LEFT_KNEE`          | `3D`, `XY`      |
| `LEFT_FOOT_STRIKE`        | Left Foot Strike Angle        | Foot-ground angle at impact (left leg)              | `LEFT_KNEE`, `LEFT_ANKLE`, `LEFT_FOOT_INDEX`        | `3D`, `YZ`      |
| `RIGHT_FOOT_STRIKE`       | Right Foot Strike Angle       | Foot-ground angle at impact (right leg)             | `RIGHT_KNEE`, `RIGHT_ANKLE`, `RIGHT_FOOT_INDEX`     | `3D`, `YZ`      |
| `LEFT_SHOULDER_ABDUCTION` | Left Shoulder Abduction       | Side arm lift of left shoulder                      | `THORAX`, `LEFT_SHOULDER`, `LEFT_ELBOW`             | `3D`, `XY`      |
| `RIGHT_SHOULDER_ABDUCTION`| Right Shoulder Abduction      | Side arm lift of right shoulder                     | `THORAX`, `RIGHT_SHOULDER`, `RIGHT_ELBOW`           | `3D`, `XY`      |
| `PELVIC_TILT`             | Pelvic Tilt                   | Anterior/posterior rotation of the pelvis           | `THORAX`, `MIDDLE_HIP`, `MIDDLE_SHOULDER`           | `3D`, `YZ`      |
| `TORSO_ROTATION`          | Torso Rotation                | Axial rotation of torso relative to pelvis          | `LEFT_HIP`, `THORAX`, `RIGHT_SHOULDER`              | `3D`, `XZ`      |
| `LEFT_KNEE_ALIGNMENT`     | Left Knee Alignment           | Left knee medial/lateral deviation                  | `LEFT_HIP`, `LEFT_KNEE`, `LEFT_ANKLE`               | `XY`            |
| `RIGHT_KNEE_ALIGNMENT`    | Right Knee Alignment          | Right knee medial/lateral deviation                 | `RIGHT_HIP`, `RIGHT_KNEE`, `RIGHT_ANKLE`            | `XY`            |
