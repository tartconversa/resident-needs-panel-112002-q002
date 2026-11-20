# 合成输入材料

这里的记录均为合成数据，不对应真实住户、项目或城市。每个文件表示一个来源数据表，不包含分析结论；解释记录时应保留来源标识和修订关系。

- `households.csv`：CSV 表格，字段为 `household_token, block, tenure, age_band, access_need`。日期字段使用 ISO 8601 格式；空单元格表示未知或未提供，不代表数值零。
- `invitations.csv`：CSV 表格，字段为 `invite_id, household_token, wave, channel, status`。日期字段使用 ISO 8601 格式；空单元格表示未知或未提供，不代表数值零。
- `responses.csv`：CSV 表格，字段为 `response_id, invite_id, submitted_at, need_code, revision_of, proxy`。日期字段使用 ISO 8601 格式；空单元格表示未知或未提供，不代表数值零。
- `block-boundaries.csv`：CSV 表格，字段为 `boundary_version, block, district, valid_from`。日期字段使用 ISO 8601 格式；空单元格表示未知或未提供，不代表数值零。
