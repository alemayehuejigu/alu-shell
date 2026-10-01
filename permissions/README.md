# Shell Permissions

Bash scripts covering Linux file permissions, ownership, and user management.

## Scripts

| File | Description |
|------|-------------|
| `0-iam_betty` | Switch current user to betty (`su betty`) |
| `1-who_am_i` | Print the effective username of the current user |
| `2-groups` | Print all groups the current user belongs to |
| `3-new_owner` | Change the owner of `hello` to betty |
| `4-empty` | Create an empty file called `hello` |
| `5-execute` | Add execute permission to the owner of `hello` |
| `6-multiple_permissions` | Add execute to owner+group and read to others for `hello` |
| `7-everybody` | Add execute permission to everyone for `hello` |
| `8-James_Bond` | Set `hello` permissions to `-------rwx` (007) |
| `9-John_Doe` | Set `hello` permissions to `-rwxr-x-wx` (753) |
| `10-mirror_permissions` | Mirror permissions of `olleh` onto `hello` |
| `11-directories_permissions` | Add execute to all subdirectories for all users |
| `12-directory_permissions` | Create directory `my_dir` with permissions 751 |
| `13-change_group` | Change group of `hello` to school |
| `14-change_owner_and_group` | Change owner to vincent and group to staff for all files/dirs |
| `15-symbolic_link_permissions` | Change owner+group of symlink `_hello` to vincent:staff |
| `16-if_only` | Change owner of `hello` to vincent only if owned by guillaume |