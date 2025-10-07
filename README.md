# Smart_study_planner
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Smart Study Planner</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <h1>📚 Smart Study Planner</h1>

    <div class="task-form">
      <input type="text" id="subject" placeholder="Enter Subject" />
      <input type="text" id="topic" placeholder="Enter Topic" />
      <input type="date" id="date" />
      <select id="priority">
        <option value="Low">Low Priority</option>
        <option value="Medium">Medium Priority</option>
        <option value="High">High Priority</option>
      </select>
      <button id="addTask">Add Task</button>
    </div>

    <h2>Your Study Tasks</h2>
    <ul id="taskList"></ul>
  </div>

  <script src="script.js"></script>
</body>
</html>           
