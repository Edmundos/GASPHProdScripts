# GASPHProdScripts
\\Basic batch files to make my work faster

icacls "C:\Program Files (x86)\Global Agility Solutions" /inheritance:r /T
icacls "C:\Program Files (x86)\Global Agility Solutions" /setowner Everyone
icacls "C:\Program Files (x86)\Global Agility Solutions\*.*" /setowner Everyone:F
icacls "C:\Program Files (x86)\Global Agility Solutions" /grant Everyone:F /inheritance:e /T
icacls "C:\Program Files (x86)\Global Agility Solutions\*.*" /grant Everyone:F /inheritance:e /T
