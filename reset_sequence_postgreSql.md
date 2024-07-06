## How to RESET a SEQUENCE in PostgreSQL?

### Step 1. List Sequences

```
  SELECT
	  sequence_schema,
	  sequence_name,
	  sequence_catalog
  FROM
	  information_schema.sequences s
  ORDER BY
	  sequence_name;
```

