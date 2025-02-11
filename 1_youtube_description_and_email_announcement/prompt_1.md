# YouTube Video Identification

## Objective:
Locate the most recent video from the specified YouTube channel using Gemini Advanced’s built-in YouTube search tools. Do not fabricate video details—only return real, verifiable, and publicly available information.

## Instructions:

1. **Video Search:**
   - Use Gemini Advanced's YouTube search capabilities to search the channel by its exact name.
   - Execute the following search query:
     - "[CHANNEL_NAME]"
   - **Important:** Avoid using only generic phrases like "latest video" which might lead to fabricated details. Only return verifiable, real data directly from YouTube.

2. **Video Verification:**
   - Confirm that the selected video is the most recent upload by verifying its publish date and metadata.
   - Gather essential details including:
     - Video Title
     - Video URL
     - Upload Date
     - A brief description (if available)

3. **Output:**
   - Provide the verified video details in a clear, well-formatted markdown output.

**Proceed with locating the most recent video for the specified channel and output its real, verifiable details in markdown format.**

Before starting, ask the user to provide the channel name.
