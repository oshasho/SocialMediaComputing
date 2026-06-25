# SocialMediaComputing
Future Work
To build upon the success of this project, there are three clear areas for future improvement:
1. Trying Different Text Balancing Methods
While SMOTE worked well to balance our dataset, it can sometimes create noisy synthetic data. In the future, we can try text-based balancing techniques like Back-Translation (translating English sentences into another language, like French or Malay, and then back to English). This creates brand-new sentences with the exact same meaning, providing a cleaner way to boost our minority classes.
2. Testing Faster, Lightweight Transformer Models
Using the pre-trained transformer pipeline gave us amazing results, but it takes a lot of computer memory and time to process data. Future work should test smaller, highly optimized models like MobileBERT. These models are designed to give almost the same high accuracy but run much faster, making them perfect for real-time app deployment.
3. Moving to Multimedia Content (Text + Images)
Social media isn't just made of text; people post images, memes, and videos to express their opinions. A major future direction is to upgrade this system into a multimodal pipeline that reads both text and images at the same time. By pairing our current text models with image-recognition models (like ResNet50), the system will be able to understand the full context of modern online posts.
