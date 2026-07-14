# Meet AI

Meet AI is an AI-powered meeting platform built with Python (FastAPI) and Jitsi. It features optional OpenAI intelligence, Supabase-backed authentication, meeting transcripts, automatic summaries, semantic search, and billing integration scaffolding.

---

## What the Platform Does

### 1. Audio and Video Meetings
- Integrates Jitsi for seamless video room embedding.
- Supports guest invitations via invite tokens.
- Displays an AI interviewer presence on the meeting page.

### 2. Interactive Voice Interview Mode
- Supports continuous listening with pause-based turn detection.
- Uses browser speech recognition with a server-side recording fallback.
- Offers voice-based question-and-answer interactions with the AI assistant.
- Supports interruption, allowing the AI to stop speaking when the user starts talking.

### 3. Transcript Processing and Search
- Auto-saves live transcripts in real time during the meeting.
- Offers in-app background generation of post-meeting summaries.
- Provides rolling, in-meeting summary refreshes.
- Enables embedding-based semantic search across meeting transcripts.
- Allows real-time Q&A from transcript memory during active meetings.
- Includes a toolbar search filter for live transcripts.

### 4. LangGraph Agent Workflows
- Manages the interview script and flow using stateful graphs for follow-up questions.
- Built-in observability and tracing for chat, summaries, and retrieval workflows.

### 5. Authentication and Billing
- Supports signup, login, and email verification.
- Includes subscription billing scaffolding and webhook handling.
