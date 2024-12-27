# Track new releases of Snowplow components

Sends an event to track new releases of Snowplow components. The required inputs are:
- `component` -- the component that is being released
- `version` - the new version, e.g. semver or a commit hash
- `team` - the Snowplow team that manages this component, one of the options defined at `iglu:com.snowplowanalytics.engineering/release/jsonschema/1-1-0`
