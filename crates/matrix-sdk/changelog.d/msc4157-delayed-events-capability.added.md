The widget driver now supports the `org.matrix.msc4157.get_delayed_events_capability` widget action from
[MSC4157](https://github.com/matrix-org/matrix-spec-proposals/pull/4157), and advertises the
`org.matrix.msc4157_delayed_events_capability` API version. It lets a widget granted the
`org.matrix.msc4157.send.delayed_event` capability read the delayed event limits that the homeserver advertises in
its `m.delayed_events` (or unstable `org.matrix.msc4140.delayed_events`) capability
([MSC4140](https://github.com/matrix-org/matrix-spec-proposals/pull/4140)).
