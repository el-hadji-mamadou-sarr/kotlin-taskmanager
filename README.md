# KOTLIN TASK MANAGER
A simple Android task manager application that allows users to view a list of tasks, mark them as completed, and set reminders for specific tasks.

## How It Works

### Task List
- Tasks are displayed in a RecyclerView with each row containing:
1. A title of the task (TextView).
2. A checkbox to mark it as completed (CheckBox).

### Reminders
- Users can schedule reminders for tasks.
1. When the reminder time is reached, an alarm notifies the user.

### Architecture
- Follows a simple structure:
1. MainActivity: Displays the task list.
2. TaskAdapter: Binds task data to the RecyclerView.
3. AlarmReceiver: Handles alarms and triggers reminders.
4. ReminderService: Runs in the background to send reminders for tasks.

## Installation
``git clone https://github.com/el-hadji-mamadou-sarr/kotlin-taskmanager.git``

## Screenshots
![reame-task-manager](https://github.com/user-attachments/assets/57272368-c53f-4c00-a912-9d72af5b782a)

