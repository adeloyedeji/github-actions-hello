# Hello world javascript action
This action prints "Hello World" "Hello" + the name os a person to greet to the log.

## Inputs
### `who-to-greet`
**Required** The name of the person to greet. Default `"World"`.

## Outputs
### `time`

The time we greeted you.

## Example usage
uses: actions/github-actions-hello@v1
with:
	who-to-greet: 'Mona the Octocat'