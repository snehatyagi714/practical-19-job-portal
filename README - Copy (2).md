# Northstar Careers — Practical No. 19

A responsive, multi-page job portal built with HTML, CSS, and vanilla JavaScript for the MSE2 practical assignment.

## Pages

1. `index.html` — Home and featured roles
2. `jobs.html` — Job listings, keyword/location search, and filters
3. `job-details.html` — Full role details
4. `post-job.html` — Publish a role (saved jobs appear in listings)
5. `apply.html` — Application form with PDF-only resume validation
6. `companies.html` — Company directory
7. `profile.html` — Candidate profile, saved jobs, and application list

## Run locally

Open `index.html` in a modern browser. No build step or package install is needed. This demo uses browser `localStorage` to keep saved jobs, posted roles, candidate details, and applications on the same device.

## Practical 19 checklist

- Search by keyword and location
- Filter by job type and experience level
- Save and unsave jobs; saved list appears in Candidate Profile
- Apply form accepts PDF resumes only (maximum 5 MB)
- Post a job; newly posted roles appear in Job Listings
- Responsive layout for desktop and mobile widths

## GitHub / deployment

Create a GitHub repository, upload the contents of this folder, and submit its repository URL. For an optional Vercel deployment, import that repository and use the default static-site settings (no build command; project root is this folder). Netlify can deploy the folder as a static site as well.

> This is a front-end student demo. Browser storage is local to the device; there is no server-side account or application database.
