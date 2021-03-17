
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Svane20&show_icons=true&theme=synthwave&count_private=true)

- uses: lowlighter/metrics@latest
  with:
    # ... other options
    plugin_wakatime: yes
    plugin_wakatime_token: ${{ secrets.WAKATIME_TOKEN }}      # Required
    plugin_wakatime_days: 7                                   # Display last week stats
    plugin_wakatime_sections: time, projects, projects-graphs # Display time and projects sections, along with projects graphs
    plugin_wakatime_limit: 4                                  # Show 4 entries per graph
