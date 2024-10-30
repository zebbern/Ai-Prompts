# GPT Search Prompts

Welcome to **GPT Search Prompts**! This repository is dedicated to providing a detailed and comprehensive set of search prompts designed to optimize the use of AI, like GPT, for more accurate and context-driven information retrieval. Whether you're a cybersecurity professional, researcher, or just exploring AI-powered tools, these prompts will help you refine your queries, get precise answers, and make the most of GPT's capabilities.

## Introduction

The following cheat sheet provides a complete list of prompts, search options, and example usages that are useful for guiding GPT or other AI models in retrieving specific, actionable, and reliable information. These prompts are specifically tailored to help you:

- **Optimize search accuracy**: Customize searches to get relevant and detailed responses.
- **Refine information retrieval**: Narrow down results based on keywords, sources, or timeframes.
- **Simplify complex searches**: Combine options to address specific use cases.

## How to Use This Guide

Each option in the following table offers a unique parameter that you can use to control the kind of search results you want to generate. Combine multiple options to get customized results for specific use cases, whether for penetration testing, threat intelligence, or general information gathering.

## Page Setup Summary:

- **Queries For Specific Cases**
- **Example Combined Queries**
- **Specific links Search**
- **Contributions**
---

| **Option** | **Description** | **Example Usage** |
| --- | --- | --- |
| `query` | Main search term or topic | `query="latest cybersecurity trends"` |
| `recency_days` | Filter results to only show those from the past specified days | `recency_days=30` |
| `include_keywords` | Prioritize certain keywords in search results | `include_keywords=["APT", "phishing"]` |
| `exclude_keywords` | Exclude certain keywords from search results | `exclude_keywords=["advertisement", "promotion"]` |
| `source_priority` | Specify preferred sources for more reliable results | `source_priority=["MITRE", "NIST", "OWASP"]` |
| `summarize_results` | Automatically summarize the key points from each search result | `summarize_results=True` |
| `include_snippets` | Include short text snippets in search results for quick preview | `include_snippets=True` |
| `output_format` | Set the output format for results, such as table, bullet points, etc. | `output_format="table"` |
| `result_type` | Specify type of content you want to retrieve, like guides, research papers, or news | `result_type="tutorial"` |
| `technical_depth` | Control the level of technical depth for results (e.g., beginner, intermediate, advanced) | `technical_depth="advanced"` |
| `region` | Focus results on specific geographical regions | `region="EU"` |
| `language` | Set the language for search results | `language="English"` |
| `recurrence` | Set up a recurring search to retrieve updated information periodically | `recurrence="weekly"` |
| `time_range` | Specify an exact time range for results | `time_range="2023-01-01 to 2023-12-31"` |
| `group_by` | Group search results by subtopic (e.g., vulnerability type, threat actor) | `group_by="vulnerability_type"` |
| `cluster_by` | Organize results by source, publication, or other criteria | `cluster_by="source"` |
| `author` | Restrict results to publications by a specific author or expert | `author="Bruce Schneier"` |
| `min_cite_score` | Filter for research with a minimum citation score, for higher academic rigor | `min_cite_score=50` |
| `sentiment` | Filter results based on sentiment, such as positive, neutral, or negative | `sentiment="positive"` |
| `contrasting_opinions` | Include contrasting or diverse opinions to show both sides of a topic | `contrasting_opinions=True` |
| `auto_save` | Automatically save search results for future reference | `auto_save=True` |
| `translate_to` | Translate search results to a specified language | `translate_to="English"` |
| `notify_on_update` | Set up notifications if new results are available for the same topic | `notify_on_update=True` |
| `rank_by` | Set the ranking criteria for results, such as by relevance, popularity, or publication date | `rank_by="popularity"` |
| `min_relevancy_score` | Only show results above a specified relevancy score to focus on highly relevant articles | `min_relevancy_score=80` |
| `interactive_mode` | Enable interactive elements, such as links or quick actions | `interactive_mode=True` |
| `visualize_data` | Generate charts or graphs from data-driven search results, like trend or time-series analysis | `visualize_data="trend_chart"` |
| `export_format` | Export results in a specific format (e.g., CSV, PDF) for easier offline analysis | `export_format="CSV"` |
| `max_results` | Limit the number of results to a specific amount for quicker response times | `max_results=10` |
| `fast_mode` | Enable faster, less detailed results if speed is a priority | `fast_mode=True` |
| `document_type` | Specify the document type, such as white paper, report, guide, or policy document | `document_type="white paper"` |
| `peer_reviewed` | Filter for peer-reviewed documents only (useful for academic research) | `peer_reviewed=True` |
| `show_metadata` | Display metadata, such as publication date, author, and source type, with results | `show_metadata=True` |
| `highlight_keywords` | Highlight specific keywords within search results for quicker scanning | `highlight_keywords=["malware", "ransomware"]` |
| `cross_reference_sources` | Find articles or papers that cross-reference specified sources or authors | `cross_reference_sources=["SANS Institute", "Harvard"]` |
| `industry_focus` | Narrow down results to a specific industry, like healthcare, finance, or government | `industry_focus="finance"` |
| `geospatial_filter` | Filter results based on geographical context, such as attacks originating from specific regions | `geospatial_filter="North America"` |

---

### Example Combined Queries for Specific Use Cases

Here are some advanced examples combining multiple options from the cheat sheet to give you an idea of how to leverage these prompts effectively:

1. **Pentesting Guide with Advanced Tools**:
    ```
    search(query="penetration testing guide", recency_days=90, result_type="guide", include_keywords=["Nmap", "Metasploit"], output_format="table", technical_depth="advanced", max_results=15)
    ```

2. **Threat Intelligence Visualization and Export for Financial Industry**:
    ```
    search(query="threat intelligence trends in finance", recency_days=30, industry_focus="finance", visualize_data="trend_chart", export_format="CSV", rank_by="popularity", include_snippets=True)
    ```

3. **Multi-Language Cybersecurity Policy Documents for Compliance**:
    ```
    search(query="cybersecurity policy updates", recency_days=60, document_type="policy", language="French", translate_to="English", show_metadata=True, cluster_by="region")
    ```

4. **Quick Performance-Based Search on Cloud Security for the EU Region**:
    ```
    search(query="cloud security best practices", recency_days=30, region="EU", fast_mode=True, rank_by="relevance", max_results=5)
    ```

5. **Exportable Phishing Awareness Resources for Employee Training**:
    ```
    search(query="phishing awareness training materials", recency_days=60, result_type="tutorial")
    ```

6. **Privilege Escalation & Exploits for Red Team Assessments**:
    ```
    search(query="Windows privilege escalation techniques", recency_days=30, exploit_type="privilege escalation", CVE_filter=True, include_snippets=True, TTP_mapping=True)
    ```

7. **Blue Team Threat Hunting with Focus on MITRE ATT&CK TTPs**:
    ```
    search(query="threat hunting methods for detecting lateral movement", recency_days=60, threat_hunting_methods=True, TTP_mapping=True, SIEM_integration="Splunk", output_format="table")
    ```

8. **Reconnaissance Tools for Passive OSINT and Subdomain Enumeration**:
    ```
    search(query="passive OSINT tools for subdomain enumeration", recency_days=90, passive_vs_active_recon="passive", subdomain_enum_tools=True, honeypot_detection=True, include_snippets=True)
    ```

9. **Coding for Exploit Development with Python Focus**:
    ```
    search(query="Python scripting for exploit development", recency_days=30, script_language="Python", code_samples=True, obfuscation_methods=True, development_environment="Kali Linux")
    ```

10. **Community Discussions on Ethical Hacking Certification Paths**:
    ```
    search(query="OSCP certification preparation resources", recency_days=90, ethical_hacking_certifications=["OSCP"], active_discussions=True, output_format="bullet_points")
    ```

## Extra thats useful if you also have specific links you want it to take information from
### Just remember to change the links to your own
```
Please search the latest information from reputable sources, including but not limited to:

- Vulnerability databases: CVE ([**https://cve.mitre.org/**](https://cve.mitre.org/)), NVD ([**https://nvd.nist.gov/**](https://nvd.nist.gov/)), and VulnDB ([**https://vulndb.cyberriskanalytics.com/**](https://vulndb.cyberriskanalytics.com/))
- Cybersecurity news and blogs: The Hacker News ([**https://thehackernews.com/**](https://thehackernews.com/)), Cybersecurity News ([**https://www.cybersecuritynews.com/**](https://www.cybersecuritynews.com/)), and Dark Reading ([**https://www.darkreading.com/**](https://www.darkreading.com/))
- Online forums and communities: Reddit's netsec community ([**https://www.reddit.com/r/netsec/**](https://www.reddit.com/r/netsec/)), Stack Overflow ([**https://stackoverflow.com/**](https://stackoverflow.com/)), and GitHub ([**https://github.com/**](https://github.com/))

Using the latest information from these sources, please answer the following question:

[Insert your question here]

```
```
Please search the latest information from reputable sources, including but not limited to:

- Vulnerability databases: CVE ([**https://cve.mitre.org/**](https://cve.mitre.org/)), NVD ([**https://nvd.nist.gov/**](https://nvd.nist.gov/)), and VulnDB ([**https://vulndb.cyberriskanalytics.com/**](https://vulndb.cyberriskanalytics.com/))
- Cybersecurity news and blogs: The Hacker News ([**https://thehackernews.com/**](https://thehackernews.com/)), Cybersecurity News ([**https://www.cybersecuritynews.com/**](https://www.cybersecuritynews.com/)), and Dark Reading ([**https://www.darkreading.com/**](https://www.darkreading.com/))
- Online forums and communities: Reddit's netsec community ([**https://www.reddit.com/r/netsec/**](https://www.reddit.com/r/netsec/)), Stack Overflow ([**https://stackoverflow.com/**](https://stackoverflow.com/)), and GitHub ([**https://github.com/**](https://github.com/))

Using the latest information from these sources, please answer the following question:

[Insert your question here]
```

### Contributions

If you would like to contribute, please feel free to fork this repository, add your own examples, or improve existing prompts. Your input will help make this resource even more powerful and useful for everyone involved.

---

Thank you for checking out **GPT Search Prompts**. I hope these tools help you get the best out of AI-powered search. If you have any questions or suggestions, feel free to open an issue!

Happy searching! 🎉

