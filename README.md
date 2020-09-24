# bprys

**B**itbucket **p**ull **r**equest anal**y**tic**s**


# Rubygem

This is a ruby gem which helps organization to figure out the bottle neck in the PR merge process.

PRs are the heart of the engineering. How can we do better.

## Development

Clone the repo.

You will need Ruby 2.7.x

```

bundle install

```

# Running

```

cd bprys

```


```

./bin/bprys -p bitbucket -t <username in bitbucket>:<personal app pw> lendsmartlabs/esy_ui -s closed

```

[How to create an apppassword in bitbucket](https://support.atlassian.com/bitbucket-cloud/docs/app-passwords/)


# Output




# Our direction

We plan to add this Gem, in the rails webapp to discplay metrics along with Monday.com updates.
