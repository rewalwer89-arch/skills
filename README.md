# Managing branches within your repository

Create new branches for development and delete unused branches directly on GitHub.

## Creating a branch

Create a branch for a separate place to work on changes before opening a pull request.

> [!NOTE]
> You can only create a branch in a repository to which you have write access.

### Creating a branch via the branches overview

1. On GitHub, navigate to the main page of the repository.
2. From the file tree view on the left, select the <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-git-branch" aria-label="git-branch" role="img"><path d="M9.5 3.25a2.25 2.25 0 1 1 3 2.122V6A2.5 2.5 0 0 1 10 8.5H6a1 1 0 0 0-1 1v1.128a2.251 2.251 0 1 1-1.5 0V5.372a2.25 2.25 0 1 1 1.5 0v1.836A2.493 2.493 0 0 1 6 7h4a1 1 0 0 0 1-1v-.628A2.25 2.25 0 0 1 9.5 3.25Zm-6 0a.75.75 0 1 0 1.5 0 .75.75 0 0 0-1.5 0Zm8.25-.75a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5ZM4.25 12a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5Z"></path></svg> branch dropdown menu, then click **View all branches**. You can also find the branch dropdown menu at the top of the integrated file editor.

   ![Screenshot of the file tree view for a repository. A dropdown menu for branches is expanded and outlined in dark orange.](/assets/images/help/repository/file-tree-view-branch-dropdown-expanded.png)
3. Click **New branch**.

   ![Screenshot of the "Branches" page for a repository. A green button, labeled "New branch", is highlighted with an orange outline.](/assets/images/help/branches/new-branch-button.png)
4. Under "New branch name", type a name for the branch.
5. Under "Source", choose the branch to base your new branch on.
6. Click **Create new branch**.

### Creating a branch using the branch dropdown

1. On GitHub, navigate to the main page of the repository.

2. Select the <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-git-branch" aria-label="git-branch" role="img"><path d="M9.5 3.25a2.25 2.25 0 1 1 3 2.122V6A2.5 2.5 0 0 1 10 8.5H6a1 1 0 0 0-1 1v1.128a2.251 2.251 0 1 1-1.5 0V5.372a2.25 2.25 0 1 1 1.5 0v1.836A2.493 2.493 0 0 1 6 7h4a1 1 0 0 0 1-1v-.628A2.25 2.25 0 0 1 9.5 3.25Zm-6 0a.75.75 0 1 0 1.5 0 .75.75 0 0 0-1.5 0Zm8.25-.75a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5ZM4.25 12a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5Z"></path></svg> branch dropdown menu, in the file tree view or at the top of the integrated file editor.

   ![Screenshot of the file tree view for a repository. A dropdown menu for branches is outlined in dark orange.](/assets/images/help/branches/file-tree-view-branch-dropdown.png)

3. Optionally, to create the new branch from a branch other than the default branch of the repository, click another branch. Then, select the branch dropdown menu again.

4. In the "Find or create a branch..." text field, type a unique name for your new branch, then click **Create branch**.

   ![Screenshot of the branch selector dropdown menu. "Create branch: new-branch" is highlighted with an orange outline.](/assets/images/help/branches/create-branch-text.png)

### Creating a branch for an issue

You can create a branch to work on an issue directly from the issue page. See [Creating a branch to work on an issue](/en/issues/tracking-your-work-with-issues/using-issues/creating-a-branch-for-an-issue).

## Deleting a branch

Delete branches that you no longer need, such as branches for merged or closed work.

You can have head branches automatically deleted after pull requests are merged in your repository. See [Managing the automatic deletion of branches](/en/repositories/configuring-branches-and-merges-in-your-repository/configuring-pull-request-merges/managing-the-automatic-deletion-of-branches).

> [!NOTE]
> If the branch you want to delete is the repository's default branch, choose a new default branch first. See [Changing the default branch](/en/repositories/configuring-branches-and-merges-in-your-repository/managing-branches-in-your-repository/changing-the-default-branch).

If the branch is associated with an open pull request, merge or close the pull request before deleting the branch.

1. On GitHub, navigate to the main page of the repository.
2. From the file tree view on the left, select the <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-git-branch" aria-label="git-branch" role="img"><path d="M9.5 3.25a2.25 2.25 0 1 1 3 2.122V6A2.5 2.5 0 0 1 10 8.5H6a1 1 0 0 0-1 1v1.128a2.251 2.251 0 1 1-1.5 0V5.372a2.25 2.25 0 1 1 1.5 0v1.836A2.493 2.493 0 0 1 6 7h4a1 1 0 0 0 1-1v-.628A2.25 2.25 0 0 1 9.5 3.25Zm-6 0a.75.75 0 1 0 1.5 0 .75.75 0 0 0-1.5 0Zm8.25-.75a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5ZM4.25 12a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5Z"></path></svg> branch dropdown menu, then click **View all branches**. You can also find the branch dropdown menu at the top of the integrated file editor.

   ![Screenshot of the file tree view for a repository. A dropdown menu for branches is expanded and outlined in dark orange.](/assets/images/help/repository/file-tree-view-branch-dropdown-expanded.png)
3. Next to the branch that you want to delete, click <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-trash" aria-label="The trash icon" role="img"><path d="M11 1.75V3h2.25a.75.75 0 0 1 0 1.5H2.75a.75.75 0 0 1 0-1.5H5V1.75C5 .784 5.784 0 6.75 0h2.5C10.216 0 11 .784 11 1.75ZM4.496 6.675l.66 6.6a.25.25 0 0 0 .249.225h5.19a.25.25 0 0 0 .249-.225l.66-6.6a.75.75 0 0 1 1.492.149l-.66 6.6A1.748 1.748 0 0 1 10.595 15h-5.19a1.75 1.75 0 0 1-1.741-1.575l-.66-6.6a.75.75 0 1 1 1.492-.15ZM6.5 1.75V3h3V1.75a.25.25 0 0 0-.25-.25h-2.5a.25.25 0 0 0-.25.25Z"></path></svg> .

   ![Screenshot of a branch in the branch list. A trash icon is highlighted with an orange outline.](/assets/images/help/branches/branches-delete.png)
4. If the branch is associated with at least one open pull request, deleting the branch closes the pull requests. Read the warning, then click **Delete**.

If you delete a head branch after its pull request has been merged, GitHub checks for any open pull requests in the same repository that specify the deleted branch as their base branch. GitHub automatically updates any such pull requests, changing their base branch to the merged pull request's base branch.
See [Branches](/en/pull-requests/reference/branches).

## Further reading

* [Branches](/en/pull-requests/reference/branches)
* [Viewing branches in your repository](/en/repositories/configuring-branches-and-merges-in-your-repository/managing-branches-in-your-repository/viewing-branches-in-your-repository)
* [Deleting and restoring branches in a pull request](/en/repositories/configuring-branches-and-merges-in-your-repository/managing-branches-in-your-repository/deleting-and-restoring-branches-in-a-pull-request)# ngrok Agent Skills

A collection of skills for AI coding agents, covering how to expose local services, route and secure traffic, receive webhooks, and more.

Skills follow the [Agent Skills](https://agentskills.io/) format, so this repo works as a standalone skill pack and as a plugin for Claude Code, Cursor, ChatGPT, and Codex.

## Installation

Any [Agent Skills](https://agentskills.io/)-compatible agent:

```bash
npx skills add ngrok/skills
```

Or install as a plugin:

- **Claude Code** (adds `/ngrok:*` slash commands):

  ```
  /plugin marketplace add ngrok/skills
  /plugin install ngrok@ngrok
  ```

- **Cursor:** Customize → Plugins → Add marketplace → From GitHub Repository → `ngrok/skills`.
- **ChatGPT and Codex:** run the command below, then restart and install **ngrok** from the Plugins Directory.

  ```bash
  codex plugin marketplace add ngrok/skills
  ```

## Skills

| Skill                      | Covers                                                                                                                                | Use when                                                                                             |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `expose-localhost`         | Give a local service a public URL — HTTP, or raw TCP for SSH, RDP, and databases                                                      | "Expose my local server", "Make my app publicly accessible", "SSH into a box with no public IP"      |
| `secure-endpoint`          | Auth, rate limiting, IP rules, or a custom response in front of an endpoint, without touching application code                        | "Require Google login on my ngrok URL", "Only allow my office IP range", "Put up a maintenance page" |
| `receive-webhooks`         | Receive webhooks from Stripe, GitHub, and 70+ other providers, with signature verification at the edge                                | "Test Stripe webhooks locally", "One endpoint for webhooks from several providers"                   |
| `run-mcp-gateway`          | Expose an MCP server under development so Claude, OpenAI, or another provider can connect to it, each with its own credential         | "Let Claude connect to my local MCP server"                                                          |
| `provision-sandbox-access` | Give every sandbox, container, customer device, or tenant its own isolated endpoint, provisioned programmatically from a controlplane | "Each sandbox needs its own SSH access", "One endpoint per customer"                                 |
| `troubleshoot-ngrok`       | Diagnose any ngrok error from its docs page and your account's live state                                                             | "What does ERR_NGROK_3200 mean?", "Works on localhost, 400 through the ngrok URL"                    |
| `ngrok-setup`              | Get authenticated and pointed at the right surface — CLI, SDK, API, or infrastructure-as-code                                         | "Set up ngrok", "ngrok says I'm not authenticated"                                                   |

### Supporting References

Two skills are reference material rather than tasks. The skills above load them automatically — you do not invoke them directly, but they're installed as part of the set.

| Skill            | Covers                                                                                                                                                          |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `ngrok-engine`   | Endpoint types (agent, cloud, internal), HTTP vs TCP, and Traffic Policy — the rule language, plus a reference for all 26 traffic policy actions                |
| `ngrok-surfaces` | How to apply configuration on each surface: agent CLI and `ngrok.yml`, the Go/JavaScript/Python/Rust SDKs, the REST API, Terraform, and the Kubernetes Operator |

## ngrok MCP server

When the ngrok MCP server is connected, the skills use it to check your account's live state, such as endpoints, agents, and traffic, instead of asking you. The plugin installs include the server. To sign in or set it up another way, see the [ngrok MCP server docs](https://ngrok.com/docs/mcp-server).

## Usage

Skills are automatically available once installed. The agent uses them when a relevant task is detected.

**Examples:**

```
Expose my app on port 3000 to the internet
```

```
Share my local server with Google OAuth so only people at @mycompany.com can access it
```

```
Receive Stripe webhooks and deliver them to a service that isn't publicly reachable
```

In Claude Code, you can also invoke a skill directly:

```
/ngrok:expose-localhost
```

Each skill contains:

- `SKILL.md` — instructions for the agent
- `references/` — supporting documentation (optional)

## Releases

Every merge to `main` that changes `skills/` (or the bundle script) publishes a dated release, after the same checks as a pull request (`.github/workflows/release.yml`). A maintainer can also run the workflow by hand from `main`. The newest release is always at `https://github.com/ngrok/skills/releases/latest`.

### Version format

- **Tag.** The tag is `v` followed by the version, for example `v2026.11.04`.
- **Version.** The version is the UTC date of the release run, written as `YYYY.MM.DD` with a zero-padded month and day.
  - The first release of a UTC day has no suffix.
  - Each later release that day appends `.N`, starting at `.1`: `2026.11.04`, then `2026.11.04.1`, then `2026.11.04.2`.
- **Ordering.** Compare versions segment by segment as integers, and treat a missing segment as 0. So `2026.11.04` < `2026.11.04.1` < `2026.11.04.10` < `2026.11.05`. Do not compare them as strings: `.10` sorts before `.9` as text.
- **Not semver.** The zero padding makes the version invalid semver. That is acceptable, because nothing reads these tags as semver. Do not copy the version into the plugin manifests' version fields. If a plugin format later needs a version, that is separate work.
- **Strictly increasing.** Every new tag must be greater than every existing `v*` tag. A same-day suffix and a UTC clock keep it that way. The workflow also checks it (`scripts/next_version.py` exits non-zero otherwise).

The reference implementation of the ordering rule is `version_key()` in [`scripts/next_version.py`](scripts/next_version.py). Anything that compares skills versions should implement the same rule.

### Assets

Each release carries two files:

| Asset | Contents |
| --- | --- |
| `skills.tar.gz` | One top-level directory per skill, with that skill's files, and nothing else. There is no wrapping `skills/` directory. Built with `git archive` of the committed `skills/` tree by [`scripts/build_bundle.sh`](scripts/build_bundle.sh). |
| `skills.tar.gz.sha256` | One line in `sha256sum` format: `<hex>  skills.tar.gz`. |

Releases are immutable: once published, a release's assets and tag cannot change.

To fetch the newest release without the GitHub API, read the `Location` header of `https://github.com/ngrok/skills/releases/latest` without following it. It ends in `/releases/tag/v<version>`. Then download `https://github.com/ngrok/skills/releases/download/v<version>/skills.tar.gz` and `skills.tar.gz.sha256`.

## License

MIT
