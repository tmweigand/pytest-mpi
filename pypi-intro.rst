This is a forked version of `pytest_mpi`

`pytest_mpi` is a plugin for pytest providing some useful tools when running
tests under MPI, and testing MPI-related code.

To run a test only when using MPI, use the `pytest.mark.mpi` marker like:
::

    @pytest.mark.mpi
    def test_mpi():
        pass


Further documentation can be found at `<https://pytest-mpi.readthedocs.io>`_.

Bug reports and suggestions should be filed at
`<https://github.com/tmweigand/pytest-mpi/issues>`_.