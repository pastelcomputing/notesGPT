# NotesGPT

Your AI journal take notes on the go with your voice and translate them into action items.

# TODOs

## v0.5 - basics

- [x] Add recording audio on the frontend
- [x] Record mp3 on the frontend and save it to ByteScale
- [x] Add whisper v3 endpoint through Fal that will take an mp3 and return the transcript
- [x] Switch from ByteScale to Convex File storage
- [x] Working version of recording audio, uploading it to Convex, and returning the transcript

## v0.7 - frontend

- [x] Implement frontend: dashboard
- [x] Implement frontend: todo list
- [x] Implement frontend: Main recording page
- [x] Implement frontend: Landing Page
- [x] Clean up code

## v1 - backend + polish

- [x] Display the transcript in the frontend
- [x] Switch to Replicate for whisper endpoint (https://replicate.com/vaibhavs10/incredibly-fast-whisper)
- [x] Add GPT-4 Turbo call to format notes into bullet points + add action items
- [x] Add auth with Clerk through Convex
- [x] Troubleshoot auth not working
- [x] Integrate frontend + backend
- [x] Edit styles on the dashboard page to make sense

## v1.5 - the convex way

- [x] Move the OpenAI and Replicate call to Convex actions
- [x] Add Convex DB to store transcripts + user action items
- [x] Change frontend to use the Convex functions and state and not the API endpoints
- [x] Navigate to new route with the note ID when it's created
- [x] Finalize the quick-check page while fetching from the DB
- [x] Keep going over dyanmic route starting line 134 to cleanup then move mobile and desktop into separate components
- [x] Move action items to their own table in the schema
- [x] Finalize the action items page while fetching from DB
- [x] Make action items work when you click them they should be deleted
- [x] Deploy to Vercel and make sure it works well
- [x] Add profile picture to the top right
- [x] Add the right links to homepage
- [x] Implement the dashboard fetching all notes + ability to delete notes

## v2 - polish & UX

- [x] Add OG image and any neccesary OG data
- [ ] Add dropdown to profile header where folks can sign in and sign out like roomGPT
- [ ] Add appropriate loading and error states everywhere
- [ ] Go through all of the code and do a cleanup, make font smaller and make sure each screen looks good
- [ ] Make sure mobile works well + fix mobile action items to look well
- [ ] Add Convex vector search for searching through transcripts
- [ ] Action items: Make it so that folks can only mark tasks done through the checkbox + add a toast to make it more obvious that a task has been marked done
- [ ] Make sure you can cross out action items from the recording screen as well
- [ ] Make full README with tech + architecture diagram
- [ ] Add technologies used in the footer
- [ ] Write up "the convex way
- [ ] Add "how it works" section to landing page

## Future tasks

- [ ] Prompt engineer the summary a little more to return something better than what it does
- [ ] Make action items animate out + make checkbox rounded + add a little check icon on hover
- [ ] Add a due date for the action items + make this editable
- [ ] Make sure the transcript gets streamed into the frontend?
- [ ] Convex scheduled functions to send initial email to user that says "welcome"
