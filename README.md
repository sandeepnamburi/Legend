# Legend
Website that generates captions based on a given picture using machine learning

# What did we build
Coming up with captions is difficult and common task for many in our generation. Rather than texting ten of your friends and google searching for hours, Legend will detect your facial expression using Google Could API and generate a clever caption for you based on that emotion. We've built our core application on a standard web application so it would be open for all PC, Mac, and mobile devices. We've utilized the fetch API to communicate with our front-end and back-end. The back-end was written in pure Node.JS and the front-end was written in HTML, CSS, and Javascript.

# How we built it
We used the Google Cloud Vision API to detect emotion in pictures. The emotions all connect to a database of captions based on the likelihood of the mood. For instance, if the API detects your mood as "joyful," then we have a series of captions that range the magnitude of joyful. We have captions for moderately joyful, very joyful, and extremely joyful. We would potentially generate captions for all of them based on the magnitude of the particular emotion. We made sure to relate to social trends for the captions.

# What inspired us
We know it's a struggle.
