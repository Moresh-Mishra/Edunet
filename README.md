<h1>Water Leak Detection System</h1>
    <h3>EduNet Final Project</h3>

  <h2>Project Overview</h2>
    <p>
        This project focuses on building a <b>machine learning–based water leak detection system</b> 
        using structured sensor data from water pipelines. The goal is to automatically predict 
        whether a pipe segment is leaking or not, based on physical and environmental measurements.
    </p>
    <p>
        Water leaks cause massive water loss, infrastructure damage, and high maintenance costs. 
        By using machine learning, this system helps detect leaks early, enabling faster maintenance 
        and better water management.
    </p>

   <h2>Dataset Description</h2>
    <p>Each row in the dataset represents the condition of a water pipe segment. The dataset contains:</p>
    <ul>
        <li><b>Pipe ID</b> – Unique identifier for each pipe</li>
        <li><b>Flow Velocity</b> – Speed of water flowing inside the pipe</li>
        <li><b>Temperature</b> – Temperature of the water</li>
        <li><b>Pipe Material</b> – Type of pipe (PVC, metal, etc.)</li>
        <li><b>Leak Class</b> – Target variable (0 = No Leak, 1 = Leak)</li>
    </ul>
    <h2>Problem Statement</h2>
    <p>
        Given the physical and environmental parameters of a water pipe, 
        predict whether the pipe has a <b>leak</b> or <b>no leak</b>.
        This is a <b>binary classification problem</b>.
    </p>

   <h2>Machine Learning Models Used</h2>
    <p>The following models were trained and evaluated:</p>
    <ul>
        <li>
            <b>Linear Regression</b> – Used to analyze how well continuous predictions 
            can separate leaking and non-leaking pipes.
        </li>
        <li>
            <b>Logistic Regression</b> – Used to predict the probability of a leak (0 or 1).
        </li>
    </ul>

  <h2>Model Performance</h2>
    <p>
        Both models achieved very strong performance.
    </p>
    <ul>
        <li><b>Accuracy Range:</b> 0.95 to 1.00</li>
    </ul>

  <h2>Project Workflow</h2>
    <ol>
        <li>Load the dataset</li>
        <li>Preprocess the data</li>
        <li>Split into training and testing sets</li>
        <li>Train Linear and Logistic Regression models</li>
        <li>Evaluate performance</li>
        <li>Compare predictions</li>
    </ol>

   <h2>Why This Project Matters</h2>
    <p>
        Water leakage leads to major water loss and infrastructure damage. 
        This project shows how <b>machine learning</b> can be used to detect 
        leaks early, reduce wastage, and improve water management.
    </p>

   <h2>Conclusion</h2>
    <p>
        This EduNet project demonstrates that machine learning models can 
        accurately predict water leaks using sensor data. Logistic Regression 
        proved especially effective for this classification task.
    </p>
    <p>
        In the future, this system can be extended to use <b>real-time IoT sensor data</b> 
        for smart water management systems.
    </p>
