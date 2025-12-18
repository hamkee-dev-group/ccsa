# CCSA: C Code Security Analyzer

**CCSA** (C Code Security Analyzer) is an online service that provides automated, enterprise-grade security auditing and static analysis of C source code. Designed for professionals and organizations who value code quality, compliance, and robust security practices, CCSA combines industry-leading static analysis tools with advanced AI code review for comprehensive reporting.

---

## What does it do?

- **Upload C source files or archives** (`.c`, `.zip`, `.tar.gz`)
- **Automatic static analysis** using multiple tools:
  - **cppcheck** for general code issues
  - **clang --analyze** for compiler-level static checks
  - **flawfinder** for common C/C++ security flaws
  - **smatch** for deeper semantic analysis
- **AI-powered review** using GPT-4:  
  Provides a professional code audit for:
  - POSIX compliance
  - SEI CERT rules and security best practices
  - Return value discipline and error checking
  - General secure coding recommendations
- **Enterprise HTML report**:  
  After upload, you’ll get a permanent link to a readable, styled audit report that summarizes tool findings and the AI code review.

---

## How to use

1. Go to the CCSA web interface.
2. Upload a `.c` file or a compressed archive (`.zip`/`.tar.gz`) containing your C sources.
3. Click **Analyze**.
4. You’ll receive a link to a full security audit and AI review once the process completes.

---

## Example

:rocket: **Live Example Report:**  
[View Example Audit Report](https://hamkee.net/ccsa/example-flaw.html)

## Blog post

[REad the full blog post where we cover how to use CCSA](https://blog.hamkee.net/ccsa-multi-layered-c-code-security-analysis/)

---

## Why use CCSA?

- **No setup required**: Everything runs in the cloud.
- **Zero trust, zero hassle**: Your code is deleted after processing; results are delivered as a secure, private link.
- **Multiple tools + AI review**: Get the best of both worlds—classic static analysis *and* modern AI expertise.
- **Enterprise-ready reports**: Suitable for audits, compliance, and professional development pipelines.

---

## FAQ

**Q: Will my code be made public?**  
A: No. Your uploads are processed securely and deleted after analysis. Only you will know the report link.

**Q: What tools are used?**  
A: CCSA runs `cppcheck`, `clang --analyze`, `flawfinder`, `smatch`, and then submits the findings and code to GPT-4 for a combined report.

**Q: Can I download the report?**  
A: Yes, reports are permanent links and printable as PDF.

---

## Privacy

- Uploaded files are deleted after analysis.
- Reports are accessible only to users with the unique report URL.
- No code is shared or published without your consent.

---

## Disclaimer

- CCSA is for **educational and professional review purposes**.  
  It should not be your only line of defense—use in conjunction with manual code reviews and other testing.

---

## See it in action

:mag_right: [Example Report](https://hamkee.net/ccsa/example-flaw.html)

---

*For more information or support, contact the project owner at [https://hamkee.net/ccsa/](https://hamkee.net/ccsa/).*
