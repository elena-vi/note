### Confusing Tables

1. question_responses
	- related to:
		- oauth_nonces
		- oauth_request_tokens
		- oauth_tokens
	- PR: [sendgrid questions](https://github.com/vinspired/vapi/pull/296/)
	- Trello: [Send scheduled emails to volunteers](https://trello.com/c/rs2UU4U8/322-send-scheduled-emails-to-volunteers-and-capture-data-from-responses)
	- I'd suggest renaming this to something a little like `scheduled_email_responses`

2. application_answers
	- related to award application
	- a better title would be `awards_application_answers`

3. attribute_value_logs
	- user tracking table
	- need a some docs on how this tracking actually works
	- I find the name a little confusing

4. tasks
	- relates to roles
	- should be renamed to `role_tasks`

5. additional_infos
	- relates to roles
	- should be renamed to `role_additional_infos`

6. skills_required
	- relates to roles
	- should be renamed to `role_skills_required `


### Great vinspired misteries
1. v_applications
2. organizations_channels
3. channels

### More deleting

1. categories
	- left over from opportunities/events

2. user_ groups
	- once upon a time vinspired sort of sorted users into groups to allow organization admins to see group stats or something, there is a vague [doc about it](https://github.com/vinspired/vapi/blob/staging/doc/API.markdown#user-groups)
	- I don't think we use this now

3. envelopes, recipients
	- not in use
	- not sure what it was supposed to be

4. email_templates
	- pretty sure the mailers that use these templates are not in use now

5. postcodes
	- just a bunch of postcodes converted into long/lat values
	- not sure if it's used

5. regions
	- doesn't seem to be in use, not sure why this should be stored in the db
