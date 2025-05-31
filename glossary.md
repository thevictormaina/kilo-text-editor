# GLOSSARY

**Canonical mode.** Also known as _cooked mode_, where keyboard input is only sent to the program when the user presses `Enter`.

**Raw mode.** Gives full control over all user input in the terminal. Processes each keypress individually instead of buffering them until `Enter`, like cooked mode.

**tcgetattr().** Read current attributes into a struct. Comes from `termios.h`.

**tcsetattr().** Write new terminal attributes. Comes from `termios.h`

**STDIN_FILENO.** File descriptor number for standard input, usually 0. Reads input from keyboard. Comes from `unistd.h`.

**termios.** POSIX extension widely available in UNIX systems.

**flag.** Bitfield, or single binary value, for toggling a behavior on or off.

**c_iflag.** Input flags. Control how input is interpreted.

**c_oflag.** Output flags. Control how output is formatted.

**c_lflag.** Local flags. Local modes like `ECHO`, cooked mode, or signals.

**c_cflag.** Control flags. Hardware control.

**TCSAFLUSH.** "Timing" flag used in `tcsetattr()`. Wait for pending output to be written and discard unread input.

**struct.** Simple custom data type that holds multiple related values. Similar to object in JavaScript, but without functions or methods.

## Course Source
https://viewsourcecode.org/snaptoken/kilo/
