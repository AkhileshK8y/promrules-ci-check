# promrules-ci-check
Github action to validate prom rules

Promtool github action doesn't support validation of PrometheusRule object. Issue https://github.com/peimanja/promtool-github-actions/issues/6

This repo implements a github action workflow where we read prometheus rule file from renders and check for its correctness.
