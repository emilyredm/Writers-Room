# Writers Room

Writers Room is an experimental toolkit for creative teams and solo writers developing TV series or serialized narrative projects. It offers modular tools for generating and refining show concepts, planning episodes and seasons, and storing creative memory in a persistent workspace.

This project is in its early stages and serves as a playground for exploring feedback loops, iteration, and collaborative storytelling with LLMs. It's designed to test how creative ideas evolve through human-AI interaction, with a focus on memory, revision, and long-form planning.

## Features
- Concept Generator: Generate and refine creative concepts interactively.
- Episode Generator: Tools for episode ideation and script development.
- Series and Season Planner: Plan series arcs and season structures.
- Writers Room Memory: Persistent storage for ideas and feedback.

## Directory Structure
```text
Modules/
  Concept Generator/
    UI_Concept_Generator.ipynb
  Episode Generator/
  Memory/
    writers_room_memory.json
  Series and Season Planner/
    UI_Season_Planner_Feedback.ipynb
    UI_Series_Overview_Generator.ipynb
requirements.txt
writersroom/ (virtual environment)
```


## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/emilyredm/Writers-Room.git
   cd Writers Room
   ```
2. (Recommended) Create and activate a virtual environment:
   ```bash
   python3 -m venv writersroom
   source writersroom/bin/activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
- Open the Jupyter notebooks in the `Modules/` directory to use the concept generator, season planner, and other tools.
- The memory module stores persistent data in `writers_room_memory.json`.

## Contributing
Contributions are welcome! Please open issues or submit pull requests for improvements or new features.

## License
This project is licensed under the MIT License.
