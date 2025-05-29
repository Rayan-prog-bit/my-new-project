<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Final project for the Building AI course

AI-Powered Accessibility Assistant

## Summary

Our project is an AI-driven platform designed to enhance digital accessibility for individuals with visual impairments or other disabilities. It uses computer vision, natural language processing (NLP), and speech synthesis to provide real-time descriptions of images, explain user interface (UI) elements, and offer guidance on navigating digital content. The assistant integrates seamlessly into web browsers and mobile applications to ensure that information is accessible to everyone.


##  Background

**The Problem:**
Millions of people worldwide face challenges when accessing online content due to visual impairments or motor difficulties. Traditional web content is often not optimized for assistive technologies, leaving users to struggle with image-based content, non-intuitive interfaces, or lack of descriptive metadata.

 **Frequency of the Problem:**
  According to the World Health Organization, over a billion people live with some form of disability. A significant portion of this population relies on assistive devices that often fail to keep up with rapidly evolving technology trends on digital platforms.

 **Personal Motivation:**
  Our team is driven by a shared passion for inclusivity and the belief that technological advances should benefit everyone. Having experienced firsthand the difficulties faced by family members with disabilities, we are committed to leveraging AI to empower people with disabilities to navigate the digital world more confidently.

* **Why It’s Important/Interesting:**
  This project not only addresses an urgent societal need but also challenges the current limitations of automated accessibility tools. By innovating in this space, we aim to contribute to a more inclusive digital future where everyone has equal access to online information.


## 3. Data and AI Techniques

**Data Sources:**

* **Accessibility Datasets:** Open-access datasets such as the Web Content Accessibility Guidelines (WCAG)-compliant websites and digital libraries for training on proper labeling and metadata.
* **Image Datasets:** Large-scale datasets like ImageNet and COCO that provide a wide variety of labeled images, which are crucial for training computer vision models.
* **User Feedback:** Data collected from real-world usage and direct feedback from users with disabilities to fine-tune and personalize the assistance.
* **Text Datasets:** Corpora from public domain texts and UI elements descriptions for refining natural language processing modules.

**AI Techniques Employed:**

* **Computer Vision:**
  Convolutional Neural Networks (CNNs) for image recognition to identify objects, text, and contextual elements in web images.
* **Natural Language Processing (NLP):**
  Transformer-based models (e.g., BERT or GPT variants) to interpret textual content and generate human-like descriptions for images or UI elements.
* **Speech Synthesis:**
  Text-to-Speech (TTS) technologies that convert generated textual descriptions into clear, natural-sounding audio.
* **Multimodal Learning:**
  Combining visual and textual data streams to produce contextually rich explanations and navigational assistance.

For those inclined to develop a concrete demo, a proof-of-concept might involve using an image captioning API and integrating a browser extension that reads out descriptions for images encountered on a webpage.



## 4. How Is It Used

**Context of Use:**

* **Users:**
  Primarily designed for individuals with visual impairments or cognitive disabilities, but beneficial for anyone seeking clearer content summaries or alternative user interfaces.
* **Settings:**
  The solution can be deployed as a browser plugin, mobile app, or integrated directly into operating systems’ accessibility features.
* **Stakeholders:**
  Website developers, user interface designers, and accessibility advocates can use insights from the AI-Powered Accessibility Assistant to improve overall digital accessibility standards.

**User Experience:**
The assistant operates in the background, activating when it detects inaccessible content. It then provides a synthesized audio explanation or text overlay describing images, buttons, and links, thereby bridging the gap between traditional content and accessible information delivery.


## Challenges

**What the Project Does Not Solve:**

* **Full Autonomy in Complex Scenarios:**
  The assistant might struggle with highly abstract or ambiguous content where context is extremely nuanced.
* **Universal Accuracy:**
  The system may occasionally misinterpret images or UI elements due to limitations in training data or inherent complexity.
* **Privacy Concerns:**
  Real-time data processing, particularly on sensitive content, raises privacy issues that need robust management and user consent mechanisms.
* **Adaptability to Niche Contexts:**
  Some specialized interfaces or non-standardized web content might not be fully supported by the current models.

Understanding these limitations is crucial for continuously evolving the solution and for setting accurate expectations with users and stakeholders.



## What Next

**Future Developments:**

* **Enhanced Personalization:**
  Implement machine learning models that adapt over time to individual user preferences and interaction patterns.
* **Broader Multilingual Support:**
  Expand language support to accommodate non-English speaking users, improving accessibility across global markets.
* **Integration with More Platforms:**
  Create APIs and plugins that integrate with major operating systems and popular applications for a more cohesive user experience.
* **Community-Driven Improvements:**
  Develop partnerships with accessibility advocacy groups and user communities to ensure that updates and improvements are aligned with actual user needs.
* **Regulatory Compliance and Certification:**
  Aim for certifications or compliance with international accessibility standards, ensuring that the assistant meets legal and ethical benchmarks.

---

## Acknowledgments

**Credits and Inspirations:**

* **Open Source Contributions:**
  The project builds on numerous open-source libraries, such as TensorFlow for deep learning, PyTorch for AI model implementation, and Mozilla’s Common Voice for speech data.
* **Inspiration from Existing Solutions:**
  We acknowledge insights gleaned from projects like Microsoft's Seeing AI and Google's Lookout, which have paved the way for innovative accessibility solutions.
* **Community and Research:**
  Our work is inspired by academic research in computer vision, NLP, and accessibility studies, as well as feedback from disability advocacy groups whose experiences have been invaluable.
* **Documentation and Guidance:**
  Special thanks to the developers of WCAG, whose guidelines have informed the accessibility targets we strive to meet in our project.
 
