<!-- AUTO-GENERATED from README.template.md — do not edit by hand -->
<div align="center">

# Arshil

Student developer · Java server work & full-stack web

</div>

I'm a student who builds full-stack web projects and sends fixes to open source projects. **7 merged upstream PRs** so far, mostly in Apache HugeGraph.

On [Apache HugeGraph](https://github.com/apache/hugegraph) I work on the server and PD: decoding HTTP Basic auth credentials as UTF-8, sanitizing Prometheus metric names and removing duplicated `/metrics` families, exporting per-store state and leader count gauges from PD, and documenting the changes in [hugegraph-doc](https://github.com/apache/hugegraph-doc).

On [Kiwix JS](https://github.com/kiwix/kiwix-js), the offline ZIM reader, I fix archive loading bugs: a block cache that mixed up archives with the same file name, and folder drops that only read the first 100 entries.

Outside upstream work I'm building CheckD, a care and accountability app: a [React Native and Expo mobile app](https://github.com/arshilkxwork/CheckD-mobile) in TypeScript with medication tracking, routines, streaks and nudges between people, backed by an [Express and PostgreSQL API](https://github.com/arshilkxwork/CheckD) with JWT auth.

## Upstream work

| Project | PRs | Focus |
| --- | --- | --- |
| [Apache HugeGraph](https://github.com/pulls?q=is%3Apr+author%3Aarshilkxwork+repo%3Aapache%2Fhugegraph+repo%3Aapache%2Fhugegraph-doc) | 6 merged · 1 open | Server auth and Prometheus metrics fixes, PD store gauges and leader balancing, docs.<br><sub>Latest: <a href="https://github.com/apache/hugegraph/pull/3374">#3374</a> — fix(hstore): register the graph with PD again after clear</sub> |
| [Kiwix JS](https://github.com/pulls?q=is%3Apr+author%3Aarshilkxwork+repo%3Akiwix%2Fkiwix-js) | 0 merged · 2 open | Archive loading fixes: block cache keys for same-name archives, folder drag and drop.<br><sub>Open: <a href="https://github.com/kiwix/kiwix-js/pull/1542">#1542</a> — Read every entry of a folder dropped onto the app #1545</sub> |

## Open PRs

Open pull requests in upstream projects (refreshed automatically).

- [apache/casbin#1767](https://github.com/apache/casbin/pull/1767) — fix: look up pattern tokens by group name in KeyMatch4 and KeyGet2/3
- [kiwix/kiwix-js#1542](https://github.com/kiwix/kiwix-js/pull/1542) — Read every entry of a folder dropped onto the app #1545
- [kiwix/kiwix-js#1541](https://github.com/kiwix/kiwix-js/pull/1541) — Stop the block cache mixing up archives with the same name #1544
- [apache/hugegraph#3356](https://github.com/apache/hugegraph/pull/3356) — feat(pd): add optional periodic partition leader balancing

## Stats

<p align="center">
  <img height="170em" src="https://github-readme-stats.vercel.app/api?username=arshilkxwork&show_icons=true&theme=transparent&hide_border=true&title_color=38C2FF&text_color=BDC3CF&icon_color=38C2FF&count_private=true&include_all_commits=true&hide_rank=true&hide=stars,issues&show=prs_merged&custom_title=Arshil%27s%20GitHub%20Stats" alt="GitHub stats"/>
  <img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=arshilkxwork&layout=compact&theme=transparent&hide_border=true&title_color=38C2FF&text_color=BDC3CF&card_width=445" alt="top languages"/>
</p>

## Tools

Java · JavaScript · TypeScript · React Native · Expo · Node.js · Express · PostgreSQL · HTML/CSS · Prometheus · Git

---

<sub>Auto-updated 2026-10-21 16:36 UTC · [workflow](.github/workflows/update-readme.yml)</sub>
