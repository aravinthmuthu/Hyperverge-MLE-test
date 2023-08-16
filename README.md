# Hyperverge-MLE-test

## Deep Learning Internship Assignment - HyperVerge Campus Placements

Greetings, Future colleagues! 👋

We're beyond thrilled to welcome you to the selection phase for the Deep Learning Internship at HyperVerge! Your passion and prowess have brought you here, and now it's time to take the challenge head-on. 🚀

## Your Adventure Begins Here.. 🗺️

Before you embark on this exciting journey, here are some key guidelines to help you navigate the path:

- **The Freedom to Explore:** This is an open-book test. Feel free to roam the realms of the internet, but keep in mind that collaboration with others is off-limits.
- **Understanding the Terrain:** Invest some quality time in absorbing this document to familiarize yourself with the challenges ahead.
- **Your Trusty Companions:** The HyperVerge team is here to assist you. Don't hesitate to raise your hand with any questions.
- **Race Against Time:** You have two thrilling hours, concluding at 12 PM sharp.
- **Essential Tools:** Don’t forget to make a copy of the given collab notebook and Google Drive folder before diving into your assignment.

## \***\*The Resources at Your Disposal 📚\*\***

- CRNN - https://arxiv.org/pdf/1507.05717.pdf

Without further due, here is the problem statement that you need to work on.

## \***\*The Challenges Awaits 🧠\*\***

You are about to delve into a pre-configured Google Collab notebook containing an OCR Model (CRNN). Fear not, the model is already trained, and the expected outputs are ready in the Google Drive. 🎁

The following two tasks and a bonus task have to be worked on using the outputs we generated for you using the CRNN model. Please note that Task 1 and Task 2 have higher weightage. The bonus task should be attempted only if the first two tasks are completed.

- **Task 1 - The Duplicate Dilemma 🧩**

  Task 1 - Ensure the OCR output does not have any duplicate character predictions.

  Details - CRNN may predict characters multiple times, leading to duplicates. Your quest begins with implementing a post-processing function to rectify this.

  For instance,

- **Task 2 - Confidence Crusade 🛡️**

  Task 2 - Calculate a single probability score for each OCR prediction to serve as a score indicating model confidence. Also, choose a reasonable confidence threshold to optimise for high precision and recall.

  Details - For each OCR prediction after post-processing, calculate a single probability score. This score estimates the confidence of the model for a prediction. Analyse and set a confidence threshold that gives the best precision and recall.

- **Bonus Task - The Masked Marvel 🎭 ( Attempt only after tasks 1 and 2 are completed )**

  Task 3 - Write an algorithm to predict each characters region within a single crop, and mask a part of the text in the image.

  Details - Using the predictions, localise the characters and apply a mask to the chosen characters.

  For instance, masking “CHARAN” in the following image using character regions would look like this.

## Submission instructions \***\*🏁\*\***

Congratulations on completing the tasks! Here's how to showcase your masterpiece:

1. **Submission Portal:** 📥 Use the provided Google Form to send your work.
2. **Execution over Perfection:** 💡 Share your approach, even if the implementation isn't perfect. We value your thought process as much as the result.
3. **Access Rights:** 🔒 Ensure public view access to your collab notebook before sharing. This is vital, as we need read access to review your hard work.

Your creativity, critical thinking, and code await the stage. All of us at HyperVerge are eagerly looking forward to witnessing your brilliance. Best of luck! 🌟
