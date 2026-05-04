<!DOCTYPE html>
<html>
<head>
  <title>Login</title>
  <style>
    body {
      font-family: Arial;
      background: #eef2f7;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .box {
      background: white;
      padding: 20px;
      width: 300px;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.2);
    }

    input {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
    }

    button {
      width: 100%;
      padding: 10px;
      background: #007bff;
      color: white;
      border: none;
      cursor: pointer;
    }
  </style>
</head>

<body>

<div class="box">
  <h2>Login</h2>

  <input id="email" placeholder="Email">
  <input id="password" type="password" placeholder="Password">

  <button onclick="login()">Login</button>
</div>

<script type="module">

import { initializeApp } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-app.js";
import {
  getAuth,
  signInWithEmailAndPassword
} from "https://www.gstatic.com/firebasejs/10.7.1/firebase-auth.js";

import {
  getFirestore,
  doc,
  getDoc
} from "https://www.gstatic.com/firebasejs/10.7.1/firebase-firestore.js";

const firebaseConfig = {
  apiKey: "AIzaSyARjhhYGo-_QUisiYa5AfUVqoJ3cHgLZM0",
  authDomain: "school-system-748cf.firebaseapp.com",
  projectId: "school-system-748cf",
  storageBucket: "school-system-748cf.firebasestorage.app",
  messagingSenderId: "899412742738",
  appId: "1:899412742738:web:7dc83a50b53789b196858b"
};

const app = initializeApp(firebaseConfig);
const auth = getAuth(app);
const db = getFirestore(app);

window.login = async function () {

  const email = document.getElementById("email").value;
  const password = document.getElementById("password").value;

  try {

    const userCred = await signInWithEmailAndPassword(auth, email, password);
    const uid = userCred.user.uid;

    const userDoc = await getDoc(doc(db, "users", uid));

    if (!userDoc.exists()) {
      alert("No user role found in database");
      return;
    }

    const role = userDoc.data().role;

    if (role === "admin") {
      window.location.href = "admin.html";
    } else {
      window.location.href = "student.html";
    }

  } catch (error) {
    alert(error.message);
  }
};

</script>

</body>
</html>
