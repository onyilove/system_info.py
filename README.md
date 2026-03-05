# system_info.py

A simple Python script that retrieves and displays system information such as operating system, processor, machine type, and computer name using Python built-in libraries.
import platform
import os

print("=== System Information ===")

# Operating system
print("Operating System:", platform.system())
print("OS Version:", platform.version())

# Processor
print("Processor:", platform.processor())

# Machine type
print("Machine:", platform.machine())

# Computer name
print("Computer Name:", platform.node())

# Current working directory
print("Current Directory:", os.getcwd())
