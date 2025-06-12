# Writers Room
Writers Room is an experimental toolkit for creative writers developing TV series or serialized narrative projects. It offers modular tools for generating and refining show concepts, planning episodes and seasons, and storing creative memory in a persistent workspace.

In its current early-stage form, Writers Room serves as a playground for exploring feedback loops, revision workflows, and collaborative storytelling with large language models. Its core focus is on how creative ideas evolve through human-AI interaction—preserving memory, enabling iteration, and supporting long-form narrative development.

Looking ahead, the goal is to evolve Writers Room into a full-featured application and collaborative service. Future features include multi-user support, real-time feedback, and shared memory—replicating the dynamics of a real writers’ room at scale. The vision is to empower creative teams to co-create with AI across every stage of storytelling, in writing and potentially other mediums.

This work also invites broader reflection: How might LLM-driven collaboration shape or homogenize creative expression? While risks exist, there’s also enormous potential to lower the floor for structured storytelling and unlock new modes of creative exploration. There’s also a meaningful opportunity to explore how LLMs can most effecticely navigate long-form creative context and collaborate with humans in a way that supports, rather than dilutes, the soul of human storytelling, both the process and the product.


## Features
- Concept Generator: Generate and refine creative concepts interactively.
- Episode Generator: Tools for episode ideation and script development.
- Series and Season Planner: Plan series arcs and season structures.
- Writers Room Memory: Persistent storage for ideas and feedback.

## Directory Structure
```text
Modules/
  Memory/
    writers_room_memory.json
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
