# Today I Learned - Web App

**Today I Learned** is a web application developed to allow you to record and share knowledge across different categories. The goal is to enable users to classify facts as:

- 👍 Interesting

- 🤯 Mind blowing

- ⛔️ False

This application allows you to organize and view various interesting facts about the world in different categories.


## 🌐 Visit the App

You can try out the live version of the app here:

[Try Today I Learned](https://todayilearned-v1.netlify.app/)


## 🧑‍💻 Tech

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)


## 📦 How to run

1. Clone the repository:  
```bash
https://github.com/perfidev/today-i-learned.git
```

2. Navigate to the project directory:  
```bash
cd today-i-learned/
```

3. Install the dependencies:  
```bash
npm install
```

4. **Supabase setup**
- Create an account on [Supabase](https://supabase.com/).
- Create a new project and obtain your API credentials.
- In the `supabase.js` file, add your Supabase credentials:

```javascript
const supabaseUrl = "your_supabase_url";
const supabaseKey = "your_api_key";
```

5. Start the local server:  
```bash
npm start
```

Now, access the app through your browser at [http://localhost:3000](http://localhost:3000).
