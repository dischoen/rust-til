# Unsolved mysteries
Here I collect rust snippets which I absolutely not understand at the moment.
Eventually they will move oder to idiomatics.org. I hope.

## formatter definition

```
fn fmt(&self, f: &mut fmt::Formatter<'_>) -> fmt::Result {
        write!(f, "{}", hex::encode(&self.0))
    }
```

## impl
## self and Self
https://stackoverflow.com/questions/32304595/whats-the-difference-between-self-and-self

## data.0
could be anything instead of data. I guess it's accessing struct elements or similar by numerical index.
