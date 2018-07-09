---
title : "1.Roadmap"
description : "Lectio Roadmap and Project Plan"
---

{{< cockpit >}}

## Lectio Roadmap && Project Plan 



{{<mermaid>}}
gantt
    dateFormat  YYYY-MM-DD
    title Lectio Roadmap and Project Plan

    Section Rearchitecture
      setting up in local                 : active,2018-05-23, 1d
      checking ldapjs library in local    : active, 2018-05-23, 1d
      schema for ldap                     : 2018-05-24,2d
    

    section Performance
      My Assignments                       :done, 2018-05-21,2018-05-23
      Dashboard                            :done, 2018-05-21,2018-05-23
      Our contents                         :done, 2018-05-21,2018-05-23
      Administration Section               :active, 2018-05-23,2d
      
      QA performance test                  :2018-05-16,2d

    Section Bug Fixing
      overall bugfixing                    :active, 2018-05-23,2d
    
    section Customer Onboarding
      User Onboarding Comparable Analysis :comperable-analysis, 2018-05-15, 2018-05-17

    section Administration
      Move admin sections as sub menu under Administration :done, 2018-05-08, 1d

    section Conversations
  
      Verification                         :done, 2018-04-24,2018-04-26
      Integrating with PostgreSQL          :done, postgre, 2018-04-26, 2018-04-28
      Moved to development                 :done, after postgre, 1d
      testing                              :done, testing, 1h
      create production xmpp server        :done, xmpp, 2018-05-03, 1d
      Moving to productiom                 :done, after xmpp, 1d
      Client side UI updates               :done, after xmpp, 4d
      Chat Notification on Profile         :read, 2018-05-06, 7d
      Testing / Fixing issues              :read, 2018-05-10, 4d
      Read/Unread message status           :read, 2018-05-06, 7d
      Testing / Fixing issues              :read, 2018-05-10, 4d
      User Typing notification             :done, read, 2018-05-07, 1d
      Online users in a chat room          :onlineusers, after des2, 4d
      Broadcast activity                   :activity, 2018-05-14, 1d
      Custom XMPP message types for structured activity  :custommsgtypes, after activity, 3d
      Count of unread messages             :unreadcount, 2018-05-15, 5d
      Campaign Conversations               :campaignconv, 2018-05-15, 7d

    Section Scoring Management
      Completed development                :done, 2018-04-24, 2018-05-04
      Testing                              :done, scoretesting, 2018-05-04, 3d
      Bug fixing                           :done, 2018-05-04, 4d
      UI fixing                            :done,2018-05-10, 3d
      Move to Production                   :done, produpdate, after scoretesting, 1d
      Verification                         :done, after produpdate, 3d
      Bug fixing                           :done, after score-verification, 3d
      Check comparable for display option selection  :done,2018-05-14, 2h
      Check comparable for score items with key values :done,2018-05-14, 2h
      Add an icon on top right on content page that opens Scoring tab :done,2018-05-15, 2h

    section Assignment Management
      Remind all                           :done, 2018-05-10, 2d
      Annotator on Content tab             :done, 2018-05-07, 2d
      featured image for assignments       :2018-05-17,2d

    section Campaign Service
      Hierarchical campaign listing        :done, 2018-05-07, 1d
      Moving label management to campaign  :done, labelmngt, 2018-05-10, 6d
      Move to production                   :done, labelmngt, 2h
      Subscriptions based on Interests (Campaigns, Label and Tags) :active, 2018-05-16, 3d

    section Account Management
      UI updates                           :done, 2018-04-22, 1h

    section User Management
      UI updates                           :done, 2018-04-22, 1h

    section Content Management
      UI updates                           :done, 2018-04-22, 1h

    section Action plugins
      UI updates                           :done, 2018-04-22, 1h

    section Notifications               
      Template Management                  :pending, 2018-05-10, 6d    
      
    section Chrome extension
      First version with ability to post to Lectio :done, 2018-04-18, 2018-05-01 
      Version 1 update to chrome store     :done, chrome, 2018-05-01, 4h
      Second version with notification     :done, secondver, after chrome, 4d
      Version 2 update to chrome store     :done, 2018-05-05, 4h
      Verification                         :done, 2018-05-03, 4d
      Post a job and invite resource from Upwork  :done, 2018-05-07, 4h
      Put a message to invite the resource for an interview :done, 2018-05-08, 1h
      Bug fixing                           :done, bugfix, 2018-05-14, 2d
      Forth version with hierarchical campaign nature   :done, 2018-05-14, 2d
      Version 3 with fixes update to chrome store :done, cev3sub, 2018-05-16, 4h
      Add @mention and hashtag lookups   : active, 2018-05-16, 2d
      Allow "Save as Draft"              : 2018-05-18, 2d
  


    section Firefox extension
      First version with ability to post to Lectio :done, ff, 2018-04-30, 5d
      Verification                         :done, 2018-05-03, 2d 
      Bug fixing                           :bugfix,  2018-05-16, 1d
      Submission to store                  :ffsub, after bugfix, 2h
      Second version with campaign natue and notification   :after ffsub, 2d

    section Unified Graphql endpoint
       Unified Endpoint in Devl            :done, unifiedend, after postgre, 2d
       Testing                             :done, testing, after unifiedend, 2d
       Bug fixing                          :done, after unifiedend, 2d
       Update to Production                :done, Produpdate, 1h
       Verification                        :done, after Produpdate, 4h
       performance testing                 :2018-05-16,active,2d

{{</mermaid>}}



