# Rust Cloudflare Worker Slackbot
This is a learning project for Cloudflare workers, using rust.

It is based on the
[`build-a-slackbot`](https://developers.cloudflare.com/workers/tutorials/build-a-slackbot) tutorial
but is built in rust using [`workers-rs`](https://github.com/cloudflare/workers-rs) instead of JavaScript.

## Usage
With `wrangler`, you can build, test, and deploy your Worker with the following commands: 

### Build
Compile your project to WebAssembly

`wrangler build` 

### Developer Locally
Runs your Worker locally for development (with a local server, file watcher & more)

`wrangler dev`

### Deploy to Cloudflare
NOTE: Replace `account_id` in the `wrangler.toml` config file with your own.
See other config options [here](https://developers.cloudflare.com/workers/cli-wrangler/configuration)

`wrangler publish`

Read the latest `worker` crate documentation here: https://docs.rs/worker
