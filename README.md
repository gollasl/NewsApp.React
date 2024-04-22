# NewsApp.React
Introduction:
Newsapp.react is a modern application designed for delivering news articles through a user-friendly interface. Built using React, a popular JavaScript library for building interactive user interfaces, this app stands out for its responsiveness and efficient updates. It fetches the latest news from various sources, presenting them in a well-organized format, allowing users to easily navigate through different categories like politics, technology, and sports. Its architecture likely includes features such as real-time updates, push notifications, and customizable content preferences, catering to a dynamic audience seeking timely and relevant news information. This setup leverages React's component-based architecture to ensure a seamless user experience.
Installation:
Select the blank Javascript template and continue to the Javascript dependencies downloading.
Move to the new directory (“NewsApp”)
Install the following dependencies:
npm install axios
npm install react-native-paper
Now, make your account on News API. From this website, you will get your API key. We are going to use this API key to fetch the news of our interest
We are done with the project setup and installation. Let’s quickly jump to the code part.

Code of News App in React Native Expo
Make two folders in the parent directory. One is a component and the other is screens. Inside the component folder, we are going to make the header.

components/AppBar.js
![image](https://github.com/gollasl/NewsApp.React/assets/156565847/b55fb6d9-d6d7-4006-b241-73d0cf115a24)

well, it’s a simple Header. I used react native paper for the header. You can use other javascript libraries too like, native base or others.

screens/index.js

We are going to use a class-based component for the screen. But first, let’s import all the required components.
![image](https://github.com/gollasl/NewsApp.React/assets/156565847/899fb972-179d-4a81-971d-0d02d22866dc)
Now fetch the news using Axios. But first, update your API key. Here I sent the query as Cryptocurrency, if you want cricket-related news then you can change it to cricket. The news API will fetch you cricket news.

After that, specify our requirements. In this case, we will fetch the date, title, URL, description, and urlToImage.

After the successful fetch, change the state. Now our empty array state will be updated with the data we fetched. After the successful fetch, loading will be set to false.
On the mobile screen, you will see, news title, Image, news description, and published time. You can customize the UI part. I know you are a pro designer.

But now, import these screens in App.js

App.js
![image](https://github.com/gollasl/NewsApp.React/assets/156565847/bdb5a3a7-35fa-46ad-b465-ba6f2bd028ff)
Now, open your command prompt window or terminal window and run this project using the command:
![image](https://github.com/gollasl/NewsApp.React/assets/156565847/aec4531d-adf4-4ed0-93fb-8040b3540974)

Output:
![WhatsApp Image 2024-04-21 at 19 54 50_4177c896](https://github.com/gollasl/NewsApp.React/assets/156565847/3d0c71f4-aa71-4785-81b3-21929afbec1d)

Detail explanation of the NewsApp in the video Format:

https://github.com/gollasl/NewsApp.React/assets/156565847/0ec21fa4-5d03-4c9f-b857-31fea4d9dd24



