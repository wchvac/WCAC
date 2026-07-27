# Initial Data Model

## Users

- id
- name
- email
- role
- active

## Tasks

- id
- title
- description
- owner_user_id
- due_date
- status
- priority
- created_at
- completed_at

## Customers

- id
- name
- phone
- email
- address

## Estimates

- id
- customer_id
- amount
- status
- salesperson_id
- estimate_date
- next_follow_up_date

## Jobs

- id
- customer_id
- job_number
- revenue
- direct_cost
- gross_profit
- gross_margin
- completion_date

## Procedures

- id
- title
- category
- content
- version
- updated_at
