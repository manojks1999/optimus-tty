# optimus-tty

## An Intelligent Terminal for newbies

## How to use:
- install requirements with the command `pip install -r requirements.txt`
- set the environment variable `OPENAI_API_KEY` to your OpenAI API key
- run `python optimus-tty.py` to start the shell.

## Notes:
- Always run with a virtual environment

## Examples Usecases

- Get system running time
- List all files in current directory
- Get system details

## Examples
- Get system details

    ```bash
    /Users/manojks/Downloads/engshell-main optimus-tty> get system details
    ```

    ```
    Running code:
    import platform

    system_details = {
        "system": platform.system(),
        "node": platform.node(),
        "release": platform.release(),
        "version": platform.version(),
        "machine": platform.machine(),
        "processor": platform.processor(),
    }

    print(system_details)
    {'system': 'Darwin', 'node': 'Manojs-MacBook-Air.local', 'release': '24.0.0',  'machine': 'arm64', 'processor': 'arm'}
    ```
