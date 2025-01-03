# Performance Monitoring UI

This is a simple performance monitoring app that runs on your localhost server. the app shows metrics like your memory usage, CPU usage, network stats, etc.

## Technologies Used

- **Flask**: Backend and API development.

## Prerequisites

1. Make sure you've installed python3 on your machine :)

## Installation & Setup

1. **Clone the Repository**:
    ```bash
    git https://github.com/Hamedtbf/OS-4021-Project
    cd OS-4021-Project
    ```

2. **Create a virtual environment and install the dependencies**:
    ```bash
    python3 -m venv env
    source env/bin/activate
    pip install -r requirments.txt
    ```

3. **Run the sever**:
    ```bash
    python3 src/run.py
    ```
   the server would be available at `http://localhost:8000`.

4. **How to use the API**:
   - `http://localhost:8000/info/` will show your system information
   - `http://localhost:8000/monitor` will show you monitoring ui

**presentation link**: https://docs.google.com/presentation/d/1rA_Yh0fSFnlhG_s_BDhcsx8P6127IFrvdrUfWFFBqMY/edit?usp=sharing
