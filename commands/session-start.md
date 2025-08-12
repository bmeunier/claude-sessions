Start a new development session by creating a session file in `sessions/` with the format `YYYY-MM-DD-HHMM-$ARGUMENTS.md` (or just `YYYY-MM-DD-HHMM.md` if no name provided).

The session file should begin with:
1. Session name and timestamp as the title
2. Session overview section with start time
3. Goals section (initially empty - will be filled based on user input)
4. Empty progress section ready for updates

After creating the file, create or update `sessions/.current-session` to track the active session filename.

**IMPORTANT**: After creating the session file, STOP and ask the user what they would like to work on. Do NOT immediately start coding or implementing anything. The session creation should be separate from the actual work.

Confirm the session has been created and then ask: "What would you like to work on in this session?" or similar.

Remind the user they can:
- Update the session with `/project:session-update`
- End it with `/project:session-end`
- View current status with `/project:session-current`