# SERVERLESS SWITCH REDIRECTION

A simple file which can be used across networks as `Switch` without having cloud server.
By default switches are in `Hash` form which should be mapped before deploying.
Redirections are not limited to boolean switches and can be used for strings (`chr` or `str`), numbers (`int` or `float`), even bytes.
It is recommended to limit usage to strings to prevent breakage due to possible future updates.
Personal recommendation is to encode data into `Base64` before deploying.
