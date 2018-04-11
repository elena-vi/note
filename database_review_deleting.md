### Why delete??

1. temporary_users:
    - not in use
    - should have never been created
    - just why??
2. activity_stream_items
    - not been used since 2017-06-05
    - this table could potentially be used for something else
3. user_events
    - leftover from events/opportunities refactor work
    - the table could be used for something more useful
4. opportunities, opportunities_skills, opportunity_interests, events
    - not needed, refactored into roles
5. vinspired_live, rockstar
    - looks like some sort of special signup table, doesn't seem to be used
6. JLGB_awards
    - special award for some partner
    - not been used since 2015-10-30
    - *data should be migrated to a generic awards table or something*
7. dosomething_campaigns
    - not in use
    - PURGE!
8. ratings
    - great idea for ranking roles (events at the time), but doesn't seem to have ever been in use
    - delete and recreate when we want to properly introduce something like this
9. a2dominion_postcodes
    - special partner postcodes
    - probably not in use anymore
10. get_trashed
    - no in use
    - maybe we should take this table's advice tho (wink wink)
11. social_loggers
    - not in use
    - don't know what it should be
12. promos
    - pronos
    - not in use since 2014-03-25
13. recommendations
    - not in use
    - don't know what it's supposed to me
14. goal_awards
    - something to do with awards
    - don't know what it's supposed to achieve
    - don't know if it's still in use
16. page_section_contents, page_assets, homepages, pages
    - smells like cms
17. content_flaggings, content_flags, content_flag_types, content_flag_fields
    - maybe cms?
    - not in use
18. legacy_application_answers
    - not in use
19. messages
    - not in use
20. streams
    - not in use
21. search_loggers
    - not in use??
22. user_features
    - not in use
23. skills_volunteering_records
    - not in use
    - I'm guessing this was something to do with allowing yps to add what skills they've learned when they record hours
24. volunteering_records_assets
    - not in use, maybe broken??
25. data_store_items
    - not in use???
26. admin_comments, comments
    - legend has it that apparently these were once used/needed
    - looking at the DB. never been used
27. admin_assets
    - not sure what this is
    - last used in 2015-06-16
28. temp_fix
    - looks like something that was possibly implemented during the refactoring of opportunities/events to roles
    - personally, I think this should have never been created
29. KPI_users
    - looks like some sort of special users table for some partner
30. KPI_awards
    - special awards
    - last used in 2016-03-31
31. KPI_hours
    - don't fully understand what it does
    - last used in 2015-07-22
32. KPI_brokerage
    - last used in 2016-03-31
33. team_vs
    - used once in 2013-12-17
34. TaskSquadID
    - don't know where this is used, but since tasksquad is dead so this should be dead too?
35. sessions
    - not in use
36. user_segments, user_segments_users, user_segment_types
    - I think we're thinking of implementing this
    - this table was last updated in 2013-12-16
37. assets
    - I think this is something to do with volunteering records assets
    - last updated at 2016-03-14
