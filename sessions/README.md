# Sessions Directory

This directory stores your development session files. Session files are automatically created when you use `/project:session-start [name]`.

## Files

- `.current-session` - Tracks the currently active session filename
- `YYYY-MM-DD-HHMM-name.md` - Individual session files with timestamps and names

## Usage

1. Start a session: `/project:session-start feature-name`
2. Update during work: `/project:session-update "Added authentication"`
3. Check status: `/project:session-current`  
4. List all sessions: `/project:session-list`
5. End session: `/project:session-end`

Session files are automatically created and maintained by the command system. Each session includes goals, progress tracking, git changes, and comprehensive summaries.