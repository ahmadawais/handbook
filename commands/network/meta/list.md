# wp network meta list

List all metadata associated with an object.

### OPTIONS

&lt;id&gt;
: ID for the object.

[\--keys=&lt;keys&gt;]
: Limit output to metadata of specific keys.

[\--fields=&lt;fields&gt;]
: Limit the output to specific row fields. Defaults to id,meta_key,meta_value.

[\--format=&lt;format&gt;]
: Accepted values: table, csv, json, count. Default: table

[\--orderby=&lt;fields&gt;]
: Set orderby which field.
\---
default: id
options:
 - id
 - meta_key
 - meta_value
\---

[\--order=&lt;order&gt;]
: Set ascending or descending order.
\---
default: asc
options:
 - asc
 - desc
\---

### GLOBAL PARAMETERS

These [global parameters](https://make.wordpress.org/cli/handbook/config/) have the same behavior across all commands and affect how WP-CLI interacts with WordPress.

| **Argument**    | **Description**              |
|:----------------|:-----------------------------|
| `--path=<path>` | Path to the WordPress files. |
| `--url=<url>` | Pretend request came from given URL. In multisite, this argument is how the target site is specified. |
| `--ssh=[<scheme>:][<user>@]<host|container>[:<port>][<path>]` | Perform operation against a remote server over SSH (or a container using scheme of "docker", "docker-compose", "vagrant"). |
| `--http=<http>` | Perform operation against a remote WordPress install over HTTP. |
| `--user=<id|login|email>` | Set the WordPress user. |
| `--skip-plugins[=<plugin>]` | Skip loading all or some plugins. Note: mu-plugins are still loaded. |
| `--skip-themes[=<theme>]` | Skip loading all or some themes. |
| `--skip-packages` | Skip loading all installed packages. |
| `--require=<path>` | Load PHP file before running the command (may be used more than once). |
| `--[no-]color` | Whether to colorize the output. |
| `--debug[=<group>]` | Show all PHP errors; add verbosity to WP-CLI bootstrap. |
| `--prompt[=<assoc>]` | Prompt the user to enter values for all command arguments, or a subset specified as comma-separated values. |
| `--quiet` | Suppress informational messages. |
