# OSI vs TCP/IP Network Models Visualizer

An interactive **Jupyter Notebook project** that visually compares the **OSI** and **TCP/IP** networking models using both **static diagrams** and **animated mappings**.  
This project is designed to help students clearly understand how the two models relate to each other layer-by-layer.

---

##  Project Purpose
Networking models are often difficult to understand from textbooks alone.  
This visualizer transforms theory into **interactive visuals**, making it easier to:

- Compare the number of layers
- Understand responsibilities of each layer
- See how OSI layers map to TCP/IP layers
- Observe conceptual data flow between models

---

##  Features

### Static Visualization
- Side-by-side comparison of OSI and TCP/IP layers
- Color-coded layer blocks
- Clean and readable layout

### Animated Visualization
- Smooth arrow animation showing relationships
- Step-by-step layer mapping
- Helps learners grasp abstraction differences

### Educational Focus
- Beginner-friendly design
- Suitable for classroom demonstrations
- Reinforces theoretical networking concepts

---

##  Networking Models Overview

### OSI Model (7 Layers)
| Layer | Function |
|------|---------|
| Application | User interface & services |
| Presentation | Data translation & encryption |
| Session | Session management |
| Transport | End-to-end communication |
| Network | Routing & addressing |
| Data Link | Frame transmission |
| Physical | Hardware & signals |

### TCP/IP Model (4 Layers)
| Layer | Function |
|------|---------|
| Application | High-level protocols |
| Transport | Reliable communication |
| Internet | Logical addressing & routing |
| Network Access | Physical transmission |

---

##  Requirements

- Python **3.8+**
- Jupyter Notebook / JupyterLab

### Python Libraries
Install dependencies using:

```bash
pip install matplotlib ipywidgets notebook




