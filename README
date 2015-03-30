# shindig-graph-sampledata

This repository contains randomly generated social network sample data for Apache Shindig.
XML files are UTF-8 encoded.

contents:
  data-2kpeople.xml (44,5MB)
    base set
    - 2001 people
    - 2000 addresses
    - 200 group200
    - 26982 messages 
    - 25365 activities
    - 19388 activity objects
    - 100 organizations
    - 14 applications

  data-2kpeople-more.xml (197,9MB)
    same amount of people, roughly 5 times the amount of messages and activities per person
    - 2011 people
    - 2000 addresses
    - 200 groups
    - 128180 messages
    - 127231 activities
    - 89155 activity objects
    - 100 organizations
    - 14 applications

  data-10kpeople.xml (222,8MB)
    bigger set with roughly 5 times the people
    - 10003 people
    - 2000 addresses
    - 200 groups
    - 133501 messages
    - 130534 activities
    - 99575 activity objects
    - 100 organizations
    - 14 application count


XML Structure:
  <social_data>
    <people>
      <person>
        ... //attributes
        <relations> //referenced via IDs
          <sends>
            ... //sent messages
          </sends>
          <affiliations>
            ... //relations to organizations
          </affiliations>
          <memberships>
            ... //group memberships
          </memberships>
          <friendships>
            ... //friendships, outgoing
          </friendships>
          <locations>
            ... //addresses
          </locations>
          <actions>
            ... //activities where this person is the actor
          </actions>
        </relations>
      </person>
    </people>
    <addresses>
      <address>
        ... //attributes
      </address>
    </addresses>
    <groups>
      <group>
        ... //attributes
      </group>
    </groups>
    <messages>
      <message>
        ... //attributes
        <relations>
          <receivers>
            ... //recipients by ID
          </receivers>
        </relations>
      </message>
    </messages>
    <activities>
      <activity>
        ... //attributes
        <relations>
          ... //subordinate activity objects by their IDs
        </relations>
      </activity>
    </activities>
    <activity_objects>
      <activity_object>
        ... //attributes
      </activity_object>
    </activity_objects>
    <organizations>
      <organization>
        ... //attributes
        <relations>
          <locations>
            ... //addresses by ID
          </locations>
        </relations>
      </organization>
    </organizations>
    <applications>
      <application>
        ... //attributes
      </application>
    </applications>
  </social_data>