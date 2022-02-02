# CONFIG

- set `docker-compose up -d` to iniciate containers and detach terminal
- to run rails commands put `docker-compose run web` in front
- docs -> https://docs.docker.com/samples/rails/

# Overtime-app

## Kew requirement: company needs documentation that salaried employees did or did not get overtime each week

## Models
- Post -> date:date rationale:text
- User -> Devise
- AdminUser -> STI

## Features:
- Approval Workflow
- SMS Sending -> link to approval or overtime input
- Administrate admin dashboard
- Email summary to managers for approval
- Needs to be documented if employee did not log overtime

## UI
Bootstrap -> formating
