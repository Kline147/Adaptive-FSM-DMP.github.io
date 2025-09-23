<link rel="stylesheet" href="styles.css">
<h1 align = "center">
An Adaptive FSM-DMP integrated Imitation learning method for Long-Horizon Human-Like Writing under Uncertain Disturbances
</h1>

<h2 align = "center">
Abstract
</h2>

Learning from demonstrations (LfD) offers a powerful paradigm for enabling robots to acquire human-like skills. However, it remains a challenge to address complex long-horizon manipulation tasks, as well as to cope with external uncertainties. To address these concerns above, we consider the robot multi-stroke writing task as a concrete example and propose an adaptive long-horizon skill imitation learning method to achieve human-like writing efficiently and adapt to uncertain interference in the environment. First, we combine finite state machines (FSM) and dynamic movement primitives (DMP) to model the long-horizon demonstration trajectory. Second, we propose an efficient steering-angle obstacle avoidance method based on active direction selection. When it is incorporated into the DMP as an additional forcing component, the robot gains proactive obstacle-avoidance capability while maintaining minimal deviation from the planned trajectory. Additionally, by introducing an adaptive variable impedance control strategy, the robot is able to achieve precise contact force tracking during writing tasks in dynamically uncertain environments. Finally, we conduct simulation and real-world experiments to validate the effectiveness of the proposed method in various task scenarios, including horizontal, inclined and complex plane writing tasks. The results indicate that the proposed method not only achieves high-precision reproduction of long-sequence task trajectories, but also adapts to environmental uncertainties such as obstacles and writing plane variations. 

<div class="video-row">
    <h3 class="video-title"> Sequential writing task under multiple disturbances in real world</h3>
    <video class="single-video" controls>
        <source src="mp4/5dof.mp4" type="video/mp4">
    </video>
</div>
