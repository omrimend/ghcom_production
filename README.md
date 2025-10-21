# Pip Test Case 1: .python-version

## What This Tests
Detection of Python version from `.python-version` file (highest priority for Pip projects).

## Expected
3.9.0 found through PythonVersionFile

## Files
- `requirements.txt` - Standard requirements file with a single dependency
- `.python-version` - Contains exact Python version

## Expected Behavior
Your version detection tool should detect **Python 3.9.0** from the `.python-version` file.

## Priority
This is the **highest priority** detection method for Pip projects, so it should be checked first.
