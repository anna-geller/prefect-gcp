# Prefect GCE Action
GitHub Action deploying Prefect agent as a container to the Google Compute Engine


## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `time`

The time we greeted you.

## Example usage

uses: actions/hello-world-docker-action@v2
with:
who-to-greet: 'Mona the Octocat'