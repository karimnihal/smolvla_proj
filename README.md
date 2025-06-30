
# GenAI for Robotics: Fine-Tuning SmolVLA to Pick and Place

This project explores the fine-tuning of lerobot/smolvla_base, a lightweight 450M parameter Vision-Language-Action model, for a simulated pick-and-place task. Using a small, pre-existing dataset of 25 successful demonstrations and the LeRobot framework, we specialized the general-purpose model to learn the specific actions required to pick up a cube. Our results show a dramatic improvement over the base model, which made no attempt to complete the task (0% contact rate), while our fine-tuned version actively tried to grab the object, achieving a 90% contact rate. This demonstrates that even with a limited dataset, SmolVLA can be effectively adapted to understand the intent of a specific robotic task, validating the approach of using accessible, lightweight models for robotics research and development.

**Medium Article:** https://medium.com/@henryhu1607/genai-for-robotics-fine-tuning-smolvla-to-pick-and-place-940b485e6c9b

**Video Code Walkthrough:** https://drive.google.com/file/d/1YDZ6SFyF4jK_i1e5e-xs0IV3jHA0mRyU/view?usp=drive_link