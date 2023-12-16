# Virtual Machine
A virtual machine that executes Python bytecode. Written in Python.
## Task
Detailed description of the task can be found in the [task.md](task.md) file (written in Russian).
## Installation and Configuration
- Clone the repository:
```bash
git clone https://github.com/funnydevelopment/virtualMachine.git
```
- Install virtual environment:
```bash
cd virtualMachine
python3 -m venv venv
```
- Install dependencies:
```bash
pip install -r requirements.txt
```
- Run the tests:
```bash
pytest test_public.py -vvv --tb=no
```