# BPMN_RPA: Robotic Process Automation with BPMN Diagrams

BPMN_RPA enables Robotic Process Automation (RPA) by executing workflows defined in Diagrams.net BPMN diagrams. It allows you to automate desktop tasks on both Windows and Linux systems directly from visual process models, bridging the gap between business process design and automation implementation.

## Key Features
*   Execute automation workflows defined in standard BPMN 2.0 diagrams.
*   Cross-platform support for Windows and Linux desktop environments.
*   Integrates with Diagrams.net (draw.io) for intuitive visual workflow design.
*   Built-in actions for UI automation, file operations, and system commands.

## Tech Stack
*   Python
*   BPMN 2.0 / XML
*   Diagrams.net (draw.io)
*   Platform-specific UI automation libraries

## Getting Started
1.  Clone the repository: `git clone https://github.com/zoreanuj/BPMN_RPA.git`
2.  Install dependencies: `pip install -r requirements.txt`
3.  Create a BPMN diagram in Diagrams.net and export it as XML.
4.  Run the engine: `python engine.py your_diagram.xml`