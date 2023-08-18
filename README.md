## Cypher Query

    CREATE USER <user-name>
      SET PASSWORD "<password>"
      SET PASSWORD CHANGE NOT REQUIRED
      SET STATUS ACTIVE
      SET HOME DATABASE <database-name>;
    GRANT ROLE <architect/role> TO <username>;
