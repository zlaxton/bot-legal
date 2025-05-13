# Privacy Policy for CursorAI_Bot

**Last Updated**: $(date +%Y-%m-%d)

## 1. Data Collection
- `Discord User ID` (snowflake format)
- `Server ID` (guild snowflake)
- `Command input` (processed but not stored)
- `Interaction timestamp` (ISO 8601 format)

## 2. Data Flow
```python
# Example processing (no persistent storage)
temp_data = {
    'user_id': ctx. author.id,
    'command': ctx command.name,
    'timestamp': datetime.utcnow() isoformat ()
}
