Virtual environment creation{
    python -m venv env (during the first time environment activation in case of error "Set-ExecutionPolicy -Scope Process -ExecutionPolicy Unrestricted".)
    .\env\Scripts\activate
    pip freeze > requirements.txt (packages list for backup)
}