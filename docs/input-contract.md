# Input material

All records are synthetic and refer to no real household, project, or city. A file is a source extract, not a precomputed answer. Preserve source identifiers and revisions when interpreting it.

- `households.csv`: CSV; columns `household_token, block, tenure, age_band, access_need`. Dates use ISO 8601 where present; blank cells mean unknown or not supplied, not numeric zero.
- `invitations.csv`: CSV; columns `invite_id, household_token, wave, channel, status`. Dates use ISO 8601 where present; blank cells mean unknown or not supplied, not numeric zero.
- `responses.csv`: CSV; columns `response_id, invite_id, submitted_at, need_code, revision_of, proxy`. Dates use ISO 8601 where present; blank cells mean unknown or not supplied, not numeric zero.
- `block-boundaries.csv`: CSV; columns `boundary_version, block, district, valid_from`. Dates use ISO 8601 where present; blank cells mean unknown or not supplied, not numeric zero.
