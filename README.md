# One Day Travel Itenrary Planner

Welcome to the **One Day Travel Itenrary Planner**, a Streamlit-based application that helps users plan their dream trips using AI agents. This repository contains the code for an AI-driven travel planning application, built to create personalized itineraries based on user preferences, interests, and travel details.

## Features
- 🌍 **Destination Selection**: Recommends destinations based on user inputs.
- 🤝 **Local Expertise**: Gathers local recommendations, insights, and activities.
- 🗺️ **Travel Itinerary**: Creates a comprehensive plan, including schedules, must-visit spots, and activities tailored to your interests.
- 🖥️ **Streamlit UI**: Intuitive and user-friendly interface for seamless interaction.

## Technologies Used
- **Python**: Programming language for backend logic.
- **Streamlit**: Framework for creating the web-based UI.
- **CrewAI Framework**: To manage AI agents and tasks.
- **Custom Modules**:
  - `Agents`: Handles AI agent-based functionality.
  - `Tasks`: Defines tasks for planning the trip.
  - `Tools` : Internet Search and Calculator

---

## Installation Guide

### Prerequisites
1. Python 3.7 or later
2. Streamlit installed on your machine
3. Internet connection for downloading dependencies

### Setup Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/mohammadasjadkhan/Attentions.ai_assignment.git
   cd Attentions.ai_assignment
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   streamlit run app.py
   ```

---

## Usage Instructions
1. Launch the application using the command above.
2. On the **sidebar**, input the following:
   - Current location
   - Desired destinations
   - Travel dates
   - Interests and trip details
3. Click on the **Plan My Trip** button.
4. Let the AI agents process your inputs and generate a personalized itinerary.

---

## Project Structure
```
Attentions.ai_assignment/
│
├── main.py                # Main application file
├── crewai/                # CrewAI module for managing agents and tasks
├── trip_agents/           # AI agents for trip planning
│   ├── __init__.py
│   ├── city_selection_agent.py
│   ├── local_expert.py
│   └── travel_concierge.py
├── trip_tasks/            # Tasks for managing trip planning logic
│   ├── __init__.py
│   ├── identify_task.py
│   ├── gather_task.py
│   └── plan_task.py
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

---

## Key Components

### 1. **Agents**
- `city_selection_agent`: Recommends destinations based on inputs.
- `local_expert`: Provides local tips, activities, and must-visit spots.
- `travel_concierge`: Finalizes the travel plan with detailed itineraries.

### 2. **Tasks**
- `identify_task`: Identifies top destinations and activities for the user.
- `gather_task`: Collects information about local events and experiences.
- `plan_task`: Generates a day-by-day itinerary based on the collected data.

### 3. **Streamlit UI**
- Sidebar input fields for user preferences.
- Real-time trip planning status display.
- Final trip itinerary displayed as markdown.

---

## Example Usage

Here’s an example of the input and output process:

### Input:
- **Current Location**: San Francisco, CA
- **Destination**: Paris, France
- **Travel Dates**: January 15, 2025 – January 22, 2025
- **Preferences**: "Couple trip, loves wine tasting, museums, and fine dining."

### Output:
A markdown itinerary with:
1. Recommended flights and accommodation options.
2. Day-by-day activities including museum visits, wine tours, and romantic dinners.
3. Local tips for transportation and cultural experiences.

---

## Future Enhancements
- Integration with real-time APIs for flights and accommodations.
- Use of cost optimisation algorithms using Multi-Agent-Reinforcement-Learning.
- Advanced filtering options based on budget and accessibility.
- Support for group trips and multi-destination itineraries.

---

## Contribution
Contributions are welcome! Please open a pull request or issue for feature suggestions or bug fixes.

---

## License
This project is licensed under the MIT License.

---

## Author
This project is developed and maintained by **Mohammad Asjad Khan**. 

Feel free to reach out for collaborations or feedback:
- 📧 Email: asjad0256@gmail.com
- 🌐 GitHub: [@mohammadasjadkhan](https://github.com/MohammadAsjadKhan)

Thank You! 
