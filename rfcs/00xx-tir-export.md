# Add TIR-export

    Feature Name: Add TIR-export
    Start Date: 2022 April
	Authors:
      Sebastian Boblest @SebastianBoblestETAS - Etas GmbH
      Ulrik Hjort TODO
    RFC PR: TBD
    GitHub Issue: TBD
- Feature Name: Add TIR-export
- Start Date: 2022-04-04
- RFC PR: [apache/tvm-rfcs#58]

# **Summary**

Move `.github/CODEOWNERS` to `.github/CODEOWNERSHIP` to avoid triggering GitHub’s [automatic review requests](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners#about-code-owners) and add GitHub Actions automation to a) populate review requests/cc's based on pull request (PR) thread traffic and b) ping languishing PRs.

# **Motivation**

## Guide-level explanation
As if it was already implemented, describe usage
# **Reference-level explanation**
Detailed internal things

# **Drawbacks**
Potentially difficult to implement a version that works at all stages of the transformation pipeline and for all targets 
(C, LLVM, CUDA, AOT, Graph)

# **Rationale and alternatives**

# **Future possibilities**

