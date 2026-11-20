# Nail My Interview: Mock Interview MCP server

Practice job interviews inside your AI assistant. Tell it the job you're going for, get 5 realistic interview questions, answer them one at a time, and get honest feedback on each answer.

Made by [Nail My Interview](https://nailmyinterview.com/), which also gives you [live AI answers during real Zoom, Meet or Teams interviews](https://nailmyinterview.com/).

## Connect

This is a hosted (remote) MCP server. There is nothing to install, no sign-up and no API key.

**Server URL (Streamable HTTP):**

```
https://nailmyinterview.com/api/mcp
```

Add it as a custom connector or remote MCP server in any client that supports one, for example Claude, ChatGPT (developer mode) or Cursor.

## Tools

| Tool | What it does |
| --- | --- |
| `start_mock_interview` | Takes a job title (and an optional company) and returns 5 realistic interview questions for it. |
| `get_answer_feedback` | Takes the job, the question and your answer, and returns a verdict (Strong, Good start or Needs work), what worked, the one thing to fix, and a stronger way to start the answer. |

## Try it

> "Start a mock interview for a data analyst job."

Then answer the first question in your own words. Your assistant sends the answer to `get_answer_feedback` and shows you the feedback before the next question.

## Want more practice?

- [Free mock interview with voice](https://nailmyinterview.com/mock-interview/) on the website, no sign-up
- [Interview questions and example answers](https://nailmyinterview.com/interview-questions/) for common jobs

## Privacy

Your job title, question and answer are sent to nailmyinterview.com and processed by an AI model to write the questions and the feedback. The server only logs which tool was used and the job title, not your answers. See the [privacy policy](https://nailmyinterview.com/privacy/).

It's free, with a shared daily limit. If the limit is reached, the tool says it's busy; try again later.

## Contact

support@nailmyinterview.com
