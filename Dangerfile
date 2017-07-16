warn('testだよーん！')
message('messageだよーん！')
fail('failだよーん！')

message "あれれ？ラベルがついてないよ？" if github.pr_labels.empty?

has_milestone = github.pr_json["milestone"] != nil
warn "あれれ？マイルストーンが設定されてないよ？" unless has_milestone