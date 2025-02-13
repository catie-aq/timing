# Gradio Timing Attack

## Overview

This repository contains a series of functions that are an experimental attempt of producing a proof of concept of a timing attack exploiting the use of a "==" in the internal implementation of gradio 4.19.1 as stated in the following article:

[Vulnerability](https://huntr.com/bounties/f6a10a8d-f538-4cb7-9bb2-85d9f5708124)

## Usage
### Experience

To get a response, you must follow the steps:

1. **Default Launch**:  
   After creating a venv according to the requirements.txt file, to launch the target for the attack on a local machine:
   ```bash
   python front.py
2. **Specific File Launch**:  
    To try and guess the frst letter of a password, supposing that we already dispose of the correct username (times stored in a text file as a python dict):
   ```bash
   python AttackOnGradio.py
   ```

### Additional

To see the difference in time spent on a an attempt with only one or two letters mismatched:

List of LLM choices:
```bash    
python bis.py