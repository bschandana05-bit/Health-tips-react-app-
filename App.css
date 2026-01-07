import React, { useState } from "react";
import "./App.css";

function App() {

  const [tips, setTips] = useState([]);
  const [diseases, setDiseases] = useState([]);

  const loadTips = () => {
    setTips([
      "Drink plenty of water",
      "Exercise regularly",
      "Eat balanced diet",
      "Get enough sleep",
      "Avoid junk food"
    ]);
  };

  const loadDiseases = () => {
    setDiseases([
      {
        name: "Diabetes",
        symptoms: "Frequent thirst, fatigue",
        prevention: "Healthy diet and exercise"
      },
      {
        name: "Hypertension",
        symptoms: "Headache, dizziness",
        prevention: "Reduce salt and stress"
      },
      {
        name: "Dengue",
        symptoms: "High fever, joint pain",
        prevention: "Mosquito control"
      }
    ]);
  };

  return (
    <div className="container">
      <h1>Health Tips & Disease Awareness</h1>

      <button onClick={loadTips}>Show Health Tips</button>
      <ul>
        {tips.map((tip, index) => (
          <li key={index}>{tip}</li>
        ))}
      </ul>

      <button onClick={loadDiseases}>Show Diseases</button>
      {diseases.map((d, index) => (
        <div className="card" key={index}>
          <h3>{d.name}</h3>
          <p><b>Symptoms:</b> {d.symptoms}</p>
          <p><b>Prevention:</b> {d.prevention}</p>
        </div>
      ))}
    </div>
  );
}

export default App;
