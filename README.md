# e2e-deploy-verify

SEAS `enterprise-production` 라이프사이클의 **실제 외부 배포 end-to-end 검증**용 자동 생성 저장소.

- ship 단계: 실제 PR 생성 → CI(GitHub Actions) → squash merge
- launch 단계: GitHub Pages 실제 공개 URL 배포
- canary 단계: 공개 URL 헬스/콘솔 모니터링

생성: 2026-06-07 (Claude Code `/auto` 검증 세션)
