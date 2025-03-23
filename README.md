# Hand-Exoskeleton
An assistive technology for the handicapped.

The idea of the project is the development of a hand exoskeleton that would assist a patient with limited hand mobility to perform some basic grasps. 
The patient is a 60+ yo male, thumb amputee with zero or broken tendons on the fingers of his left hand. As a result, he can barely move some of his fingers. The movement of his wrist is weak and constrained.

A compliant structure in the form of a glove and tendons is preferred over rigid linkages as it simplifies the design process and makes the use by the patient more comfortable. 3D printed tendon guides are used to route the fishing lane, used as tendons, from the fingertip through the palm.

The proposed design is supposed to be fully body-powered, so it doesn't include any motors. Usually, body powered devices take advantage of the wrist flexion/extension to actuate the fingers, but the weak wrist of the patient does not give us this option. Alternatively, the elbow will be used. Another typical solution is shoulder. the folder "Previous devices:" includes some media from previous wrist actuated devices that were developed by the doctor and his team as well as some photos of patients.

To convert the motion of the elbow to a hand grasp, a tendon is anchored on a point somewhere on the patient's bicep. After passing through a guide mounted on the forearm of the patient, the tendon is connected to 5 different tendons that correspond to each finger. These finger tendons pass through some cable guides in the palm and the phalanxes of the fingers, before they get tied to an anchor point at the fingertip. This way, the patient can close his fingers by extending his elbow.

The tendon guides designed for the glove should not affect the grasping action. Especially the anchor points, are located on the fingertips which means that they interact a lot with the grasping object. Minimum interaction is recommended, since the glove or the fingertip itself offers much better friction characteristics useful in grasping. Location of the guides and anchor points is critical, since the kinematics of the fingers can dramatically change.

To replace the absence of the thumb, two different designs are proposed. "Thumb whole with hinge" is a one-part thumb, printed using TPU that is using the inner elasticity of TPU to form its joints. "Thumb bottom part" & "thumb top part" are two parts, printed in resin, of a solid thumb and are connected using hinges printed in TPU as joints. Both designs are mounted on a 3d printed splint, that is supposed to hug the back of the hand and offer stability to the prosthetic thumb. The splint and the glove are sewn together. The splint design can be found as "Splint"

To maintain the grasp, even when the patient's elbow is flexed, some latching mechanisms are proposed. "Linear latch" has the disadvantage that it needs to be more than double in length compared to the maximum travelling distance. "Rotating latch" needs calibration and scaling to match perfectly the travelling distance of the tendon. An exoskeleton developed by "openbionics" is using a latch mechanism that could be used and can be found [here](https://github.com/OpenBionics/Body-Powered-Exoskeleton-Glove).

A later upgrade, could be the addition of a mechanism that is delaying the closing of the fingers until the elbow is fully extended, in order to simplify grasping objects located a bit far from the patient's body, since otherwise the grasp is being performed gradually while the elbow is being extended.



***EXTRA DETAILS

 It is important to have a glove that fits the patient well and is from a material similar to lycra, in order to adapt to the hand of the patient.
 
 The connection of the splint and the glove can be performed with various ways, like sewing, or clamping.
 
 The length of the prosthetic thumb and its orientation can be modified to achieve better results. The same applies to the length of the hinges and in the infill percentage and pattern of the printed parts. The use of other materials is also possible.
 
 To avoid the interaction of the tendons and the velcro strap used on the splint, the velcro strap should pass through the inside of the glove under the tendons.
 
 The use of a differential, pretension or elastic tendons is also recommended to compensate for the differnt finger lengths.
 
 The splint used to fit the patient's hand is designed using the sculpting environment of Fusion. Other CAD softwares can also be used.
 
 ***
