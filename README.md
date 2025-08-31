Merge, then restart explorer.exe from Task Manager or with this CMD
taskkill /f /im explorer.exe & timeout /t 2 /nobreak >nul & start explorer.exe
